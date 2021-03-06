# Underdispersion: A statistical anomaly in reported Covid data

Paper: https://rss.onlinelibrary.wiley.com/doi/10.1111/1740-9713.01627 (_Significance_, 2022)

The entire analysis presented in the paper can be reproduced with the provided Jupyter notebook. Frozen data is provided in the `frozen-data` folder. Final figures can be found in the `img` folder. 

------------------

Testing reported Covid-19 cases and deaths for underdispersion compared to Poisson, based on the WHO data. Each
dot is one week, 100 weeks in total. Asterisks denote p<0.05. Only countries with at least 15 weeks with p<0.05 
undispersion, or at least 4 weeks in a row, are shown. Summed weekly counts are separately tested for under-
dispersion in chunks of 10 weeks (below); countries with at least 5 significant weeks are shown.

```
  == REPORTED DEATHS ==
Albania        .................*.......**....***......*........*..*.*..*..................*.***...................
Algeria        ..........*****.**.....*...........................**...*.*.***.*...****............***.*.**....*...
Azerbaijan     ................****......*.****..*.....**.......*.*.....***..**..............*....*..*.............
Belarus        ......*.....*..******.******.****....***************************..****************.**********.***.*.
Cambodia       ..............................................................................*.......********......
Egypt          ................**...............******.**.****......**...**.***.*.............*..**.*.*..*.........
El Salvador    .........*.......**.....**..*...*****...***..**..***..**..**.****...***.*.*..*****..*.*.......*.....
Kyrgyzstan     .....................................**.......*...............*.*...*.***********..*******.*....*...
Lebanon        .........................................*..................**..*********..**....**..*.**..*********
Mongolia       ....................................................................**............****..............
Russia         ..........................................................................*.****....*..*.****.....*.
Saudi Arabia   .........**...*.*.....**.....***.***********.*.***.***********************.*..***********.**********
Serbia         ........***..*.*...****.*..*...***......***.*.**.****.******.******..............**********.**.*.**.
Syria          .........................*****.*******.*..*..****.*..*.*.....*.****.****.*.*..*...***....******.****
Turkey         ............**...*.****.*..**.**.****..*..*.**.*...***......................................*.......
Uzbekistan     ...................*..****.**..**.*........................*.........*************..********.**..***
Venezuela      ...................*.**....*.****...****.**.********.****.****.**..***.****.......*..**..*..**..**..

  == REPORTED CASES ==
Qatar          ............................................**....*****....................................***......
Tajikistan     ...............**.**********.***********..................................****......................
UAE            .......................................................................****...*.......**............

  == REPORTED DEATHS PER WEEK ==
Belarus            .         .         .         .         *         *         *         *         .         *     
Nicaragua          .         .         .         *         *         *         *         *         *         *     

     | Jan Feb Mar Apr  May Jun  Jul Aug  Sep Oct Nov Dec | Jan Feb Mar Apr  May Jun Jul Aug  Sep Oct Nov Dec | Jan
     |                        2020                        |                        2021                       |    
```
