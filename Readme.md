# RenderTheme for Mapsforge   
####  	*based on [Elevate](https://www.openandromaps.org/en/oam-forums/topic/elevate-updates-and-test-versions-news) & inspired by [Active_RT5](https://github.com/FrankSchoeneck/active_RT5)*  

### changes from [original Elevate](https://github.com/nono303/mapsforge-theme-elevate)  
- **improve saddle / pass visibility**   
  
  > - zoom-min: 14 > 12   
  > - ele: zoom-min=13   
  > - name: zoom-min=14   
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
  >   related to:  
  >   - https://josm.openstreetmap.de/wiki/Styles/sac_scale  
  >     <img src="https://josm.openstreetmap.de/raw-attachment/wiki/Styles/sac_scale/legend.png" width="360">  
  >   - https://www.okwirsindweg.ch/wanderskala-sac/  
  >     <img src="https://www.okwirsindweg.ch/wp-content/uploads/Wanderskala_T1_T2_T3_T4_T5_T6_Banner5-1140x196.jpg" width="360">  
  > - extract trail_visibility=no with a specific dash mode  
  > - lighten path overlay for foot & cycle shared  
  > - change overlay order (z-index) : hiking routes before hiking path  
  <a href="hiking_paths.svg"><img src="hiking_paths.svg" width="520"></a>
### Example of changes 
> _without hillshading, click to enlarge_

<a href=".screenshots/z12.jpg"><img src=".screenshots/z12.jpg" width="640"></a>
<a href=".screenshots/scree_rock.jpg"><img src=".screenshots/scree_rock.jpg" width="640"></a>
<a href=".screenshots/route_cycle.jpg"><img src=".screenshots/route_cycle.jpg" width="640"></a>