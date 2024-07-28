Several files for thermal emission spectra estimation.

- BandPyrometry.jl - Module with function to fit the temperature of the sample surface in predefined spectral range (Optimization.jl and OptimizationOptimJL.jl packages are used),
the spectral emissivity of the sample can be approximated as a Standard, Chebyshev, Legendre and trigonometric basis linear model
- BandPyrometryTypes.jl  - script file with type descriptions
- JDXreader.jl  - small JCAMP-DX=4.24 files reader
- Planck.jl  - Planck function derivatives and integrals
- Pyrometers.jl  - Module with various pyrometers types
- Planck_test_git.jl - Pluto notebook with Planck.jl, BandpyrometryPoint.jl EmPoint type and JDXreader.jl tests  (example of blackbody temperature fitting using zero-,first- and second order methods from Optimization.jl package)
