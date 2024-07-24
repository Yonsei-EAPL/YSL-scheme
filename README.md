# YSL-scheme

1. Yonsei surface layer (YSL) scheme based on the roughness sublayer theory (Harman and Finnegan, 2007; Lee et al. 2020)
2. Original Code Development by Dr. Junhong Lee (junhong.lee@mpimet.mpg.de) and Prof. Jinkyu Hong (jhong@yonsei.ac.kr)   
Debugging and recoding during the work based on this code (Kim et al. 2024) by Mr. Jeongwon Kim (kimjw3855@yonsei.ac.kr)
- Note that codes in the EAPL GitHub are only updated regularly.

      Record of revisions:
      Date           Programmer          Description of change
      ==========     ============        ======================
      02/17/2017     Junhong Lee         Original code
      04/17/2022     Junhong Lee         updates for ifort compiler
      05/24/2024     Jeongwon Kim        debugging for turbulent exchange coefficient for heat
      07/22/2024     Jeongwon Kim        code arranging

3. Corresponding:   
Junhong Lee (junhong.lee@mpimet.mpg.de)   
Jeongwon Kim (kimjw3855@yonsei.ac.kr)   
Jinkyu Hong (jhong@yonsei.kr / hong.jinkyu@gmail.com)    
https://eapl.yonsei.ac.kr

   
4. References:   
- Lee et al. (2020) Implementation of a roughness sublayer    
parameterization in the Weather Research and Forecasting model    
(WRF version 3.7.1) and its evaluation for regional climate   
simulations, GMD, 13, 521–536, https://doi.org/10.5194/gmd-13-521-2020
   
- Harman and Finnigan (2007) A simple unified theory for flow in the   
canopy and roughness sublayer, Bound.-Lay. Meteorol., 123, 339–363
   
- Kim et al. (2024) Enhancement of ANN-based wind power forecasting   
by modification of surface roughness parameterizations over complex   
terrain, Journal of Environmental Management, 362, 121246,   
https://doi.org/10.1016/j.jenvman.2024.121246

   
5. Precautions for use   
Currently, USGS geographical data must be used.   
It will soon be updated to be compatible with MODIS.
