Thanks to the hard work over at Unidata, the devs have made some amazing examples and I have been able to utilize them and sort of customize them for my own daily maps.

I made all the examples run in similar fashions and all have the exact latitude/longitude extents and map projection so all can easily be comparable when looking at several maps. 

'# Add state boundaries to plot
    states_provinces = cfeature.NaturalEarthFeature(category='cultural',
                                                    name='admin_1_states_provinces_lakes',
                                                    scale='50m', facecolor='none')
    ax.add_feature(states_provinces, edgecolor='black', linewidth=1)
'
        '


![alt text](https://github.com/MethaneRain/Weather-Jupyter-Notebooks/blob/master/MetPy_Unidata%20Examples/Sample%20Maps/2018/10_31/RESIZE_SIMPLE_PV_2018_10_31_12Z.png)

