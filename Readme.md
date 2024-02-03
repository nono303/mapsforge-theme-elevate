# RenderTheme for Mapsforge 

## Based on [Elevate 5.3.1](https://github.com/nono303/mapsforge-theme-elevate) / Inspired from [active_RT5](https://github.com/FrankSchoeneck/active_RT5)

### version [nono-rc2](https://github.com/nono303/mapsforge-theme-elevate/tree/nono-rc2) - 2024-02-03


- **improve saddle / pass visibility** 

  > - zoom-min: 14 > 12 
  >
  > - ele: zoom-min=13 
  >
  > - name: zoom-min=14 
  >
  > - symbol-height=10: zoom=12-13

- **improve terrain visibility / differentiation**

  > - patterns & color: rock, scree, vineyard, orchard, quarry, fell, scrub, forest meadow 
  > - zoom-min: 13~14 > 12 

- **better & sooner displaying of peak & volcano**

- **change color & reduce border#admin_level=2**

- **improve cliff**

- **change hillshading magnitude: 64 (default) > 128**

- **refactoring hiking trails**

  > - sac_scale differentiated by color only _(disabled dash for T4|T5|T6, dash modes only represent trail_visibility)_
  >
  >   related to:
  >
  >   - https://josm.openstreetmap.de/wiki/Styles/sac_scale
  >
  >     ![](https://josm.openstreetmap.de/raw-attachment/wiki/Styles/sac_scale/legend.png)
  >
  >   - https://www.okwirsindweg.ch/wanderskala-sac/
  >
  >     ![](https://www.okwirsindweg.ch/wp-content/uploads/Wanderskala_T1_T2_T3_T4_T5_T6_Banner5-1140x196.jpg)
  >
  > - extract trail_visibility=no with a specific dash mode
  >
  > - lighten path overlay for foot & cycle shared
  >
  > - change overlay order (z-index) : hiking routes before hiking path

  ![](hiking_paths.svg =300x200)