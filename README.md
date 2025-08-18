# 2d Lensboard Designs

This repository has lensboard designs for two kinds of cameras and one enlarger.

1. The directory `100mm` has lensboard designs for the Gowland Pocket View 4x5, which uses 100mm by 100mm (4" x 4") 1/16" aluminum lensboards.

   * Copal #0 lens board
   * Copal #1 lens board
   * Lens board cover with center hole (for air, or for a knob, or for a pinhole)

   These lensboards will also work with a Calumet CC400, provided that you use some rubber strips to build up the mounting point -- just copy the approach Peter used in the PocketView.

2. The directory `138mm` has lensboard designs for the Gowland 8x10 view camera, which uses 138.5mm by 138.5mm aluminum lensboards.

   * Copal #0 lens board
   * Copal #1 lens board
   * Lens board cover with center hole (for air, or for a knob, or for a pinhole)
   * Betax #3 lens board (for Wollensak ExWA III lens, 3 M2.5 screw holes)
   * Alphax #5 lens board (for Kodak Commercial Ektar 14" lens, 4 M3 screw holes)
   * Seiko lens board with S-1 bracket (with either 3 or 12 screw holes -- 12 hole variant allows you to choose the orientation of the bracket, but has not beeen tested). **See note 6 below; not on the `tested` branch.** (Used for Fujinon 210mm W S lens.) These holes are M3, but be careful with screw length and be sure you get thin nuts to make sure you have clearance.

3. The directory `omega-d2-discs` has lens disc designs for Omega D2 enlargers.
   * a blank lens disk
   * a disk for the M50 flange from Jose at [`CustomPhotoTools.com`](https://customphototools.com). This flange indeed holds M50 threaded lenses, but similar to most Copal #0 and #1 flanges, it has a further rim, which I measured out at 52.4 mm, hence a hole diameter of 52.726 mm.

In addition, there's some reference material.

1. The directory `flanges` has reversed-engineered 2D data for actual flanges.

## Notes:

1. Peter Gowland changed the designs from time to time, and offered custom models that accepted Linhof boards, among other things. You should measure your camera before fabbing any of these designs.

2. These designs are optimized for use with [SendCutSend](https://sendcutsend.com/). When ordering, I suggest you select 6061 T6 aluminum, in 0.63" thickness, and black matte powder coating. The hole dimensions are slightly enlarged to allow for the thickness of the coating.

3. The design for the AlphaX #5 is specifically for the flange that came with my Kodak Commercial Ektar 14" f/6.3. The holes in my flange are on diameters, but not on orthogonal diameters. It also appears that one set of holes is slightly offset (not centered on the origin of the flange). It is possible that the holes were added to the flange by a machine shop, rather than being original from Kodak.

4. In all cases, I increased hole diameters from nominal by 0.326mm. This takes into account the thickness of the powder coat. It's somewhat empirical!

5. Although I've tested all these with my lenses and gear (except as noted), I can't guarantee that these will work with your lenses or your cameras (or enlarger). Use these designs at your own risk.

6. In particular, the flange for the Seiko S-1 braket probably needs to be re-done using the tracing trick I used for the Comercial Ektar bracket.

     * The three holes are not appaentlhy at 120 degree angles on a common radius. So I needed to do some manual modification on the received 3-hole board.

     * The holes need to be aligned at a different angle if the lens is really to line up vertically.

   For this reason, I have a "tested" branch, which contains only tested desgins.

7. These are 2D designs intended for use with laser cutting services. The reference info is likely useful with lensboards that involve 3d components, but can't be used as-is.

8. These designs were done wtih Adobe Illustrator.
