# My Fortran Projects
[![GitHub](https://img.shields.io/badge/GitHub-gha3mi-blue.svg?style=social&logo=github)](https://github.com/gha3mi)
![Fortran](https://img.shields.io/badge/Fortran-734f96?logo=fortran&style=flat)
[![fpm](https://img.shields.io/badge/fpm-Fortran_package_manager-734f96)](https://fpm.fortran-lang.org)

All projects listed here are designed to be used as fpm (Fortran package manager) packages. Each library provides specific functionality and can be easily integrated into your Fortran projects using fpm.

Below is a brief overview of each project:

## ForCAD

[![GitHub](https://img.shields.io/badge/GitHub-ForCAD-blue.svg?style=social&logo=github)](https://github.com/gha3mi/forcad)
[![Version](https://img.shields.io/github/release/gha3mi/forcad.svg)](https://github.com/gha3mi/forcad/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/forcad/)
[![License](https://img.shields.io/github/license/gha3mi/forcad?color=green)](https://github.com/gha3mi/forcad/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/forcad/actions/workflows/fpm.yml/badge.svg)](https://github.com/gha3mi/forcad/actions/workflows/fpm.yml)

<!-- <img alt="ForCAD" src="https://github.com/gha3mi/forcad/raw/main/media/logo.png" width="640"> -->

ForCAD is A Fortran library for Geometric Modeling using NURBS (Non-Uniform Rational B-Splines).

**fpm Dependency:**
```toml
[dependencies]
forcad = { git = "https://github.com/gha3mi/forcad.git" }
```


## ForCompile

[![GitHub](https://img.shields.io/badge/GitHub-ForCompile-blue.svg?style=social&logo=github)](https://github.com/gha3mi/forcompile)
[![Version](https://img.shields.io/github/release/gha3mi/forcompile.svg)](https://github.com/gha3mi/forcompile/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/forcompile/)
[![License](https://img.shields.io/github/license/gha3mi/forcompile?color=green)](https://github.com/gha3mi/forcompile/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/forcompile/actions/workflows/ci.yml/badge.svg)](https://github.com/gha3mi/forcompile/actions/workflows/ci.yml)

<!-- <img alt="ForCompile" src="https://github.com/gha3mi/forcompile/raw/main/media/logo.png" width="640"> -->

ForCompile is a Fortran library to access the Compile Explorer API.

**fpm Dependency:**
```toml
[dependencies]
forcompile = { git = "https://github.com/gha3mi/forcompile.git" }
```

## ForMatmul

[![GitHub](https://img.shields.io/badge/GitHub-ForMatmul-blue.svg?style=social&logo=github)](https://github.com/gha3mi/formatmul)
[![Version](https://img.shields.io/github/release/gha3mi/formatmul.svg)](https://github.com/gha3mi/formatmul/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/formatmul/)
[![License](https://img.shields.io/github/license/gha3mi/formatmul?color=green)](https://github.com/gha3mi/formatmul/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/formatmul/actions/workflows/CI_test.yml/badge.svg)](https://github.com/gha3mi/formatmul/actions/workflows/CI_test.yml)

<!-- <img alt="ForMatmul" src="https://github.com/gha3mi/formatmul/raw/main/media/logo.png" width="640"> -->

ForMatmul is a Fortran library that overloads the `matmul` function to enable efficient matrix multiplication with coarray.

**fpm Dependency:**
```toml
[dependencies]
formatmul = { git = "https://github.com/gha3mi/formatmul.git" }
```

## ForDot

[![GitHub](https://img.shields.io/badge/GitHub-ForDot-blue.svg?style=social&logo=github)](https://github.com/gha3mi/fordot)
[![Version](https://img.shields.io/github/release/gha3mi/fordot.svg)](https://github.com/gha3mi/fordot/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/fordot/)
[![License](https://img.shields.io/github/license/gha3mi/fordot?color=green)](https://github.com/gha3mi/fordot/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/fordot/actions/workflows/CI_test.yml/badge.svg)](https://github.com/gha3mi/fordot/actions/workflows/CI_test.yml)

<!-- <img alt="ForDot" src="https://github.com/gha3mi/fordot/raw/main/media/logo.png" width="640"> -->

ForDot is a Fortran library that overloads the `dot_product` function to enable efficient dot product with/without coarray.

**fpm Dependency:**
```toml
[dependencies]
fordot = { git = "https://github.com/gha3mi/fordot.git" }
```

## ForOpenAI

[![GitHub](https://img.shields.io/badge/GitHub-ForOpenAI-blue.svg?style=social&logo=github)](https://github.com/gha3mi/foropenai)
[![Version](https://img.shields.io/github/release/gha3mi/foropenai.svg)](https://github.com/gha3mi/foropenai/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/foropenai/)
[![License](https://img.shields.io/github/license/gha3mi/foropenai?color=yellow)](https://github.com/gha3mi/foropenai/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/foropenai/actions/workflows/CI_test.yml/badge.svg)](https://github.com/gha3mi/foropenai/actions/workflows/CI_test.yml)

<!-- <img alt="ForOpenAI" src="https://github.com/gha3mi/foropenai/raw/main/media/logo.png" width="640"> -->

ForOpenAI is a Fortran library for OpenAI API.

**fpm Dependency:**
```toml
[dependencies]
foropenai = { git = "https://github.com/gha3mi/foropenai.git" }
```

## ForSVD

[![GitHub](https://img.shields.io/badge/GitHub-ForSVD-blue.svg?style=social&logo=github)](https://github.com/gha3mi/forsvd)
[![Version](https://img.shields.io/github/release/gha3mi/forsvd.svg)](https://github.com/gha3mi/forsvd/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/forsvd/)
[![License](https://img.shields.io/github/license/gha3mi/forsvd?color=green)](https://github.com/gha3mi/forsvd/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/forsvd/actions/workflows/ci.yml/badge.svg)](https://github.com/gha3mi/forsvd/actions/workflows/ci.yml)

<!-- <img alt="ForSVD" src="https://github.com/gha3mi/forsvd/raw/main/media/logo.png" width="640"> -->

ForSVD is a Fortran library for singular value decomposition (SVD) calculation, low-rank approximation, and image compression.

**fpm Dependency:**
```toml
[dependencies]
forsvd = { git = "https://github.com/gha3mi/forsvd.git" }
```

## ForPCA

[![GitHub](https://img.shields.io/badge/GitHub-ForPCA-blue.svg?style=social&logo=github)](https://github.com/gha3mi/forpca)
[![Version](https://img.shields.io/github/release/gha3mi/forpca.svg)](https://github.com/gha3mi/forpca/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/forpca/)
[![License](https://img.shields.io/github/license/gha3mi/forpca?color=green)](https://github.com/gha3mi/forpca/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/forpca/actions/workflows/CI_test.yml/badge.svg)](https://github.com/gha3mi/forpca/actions/workflows/CI_test.yml)

<!-- <img alt="ForPCA" src="https://github.com/gha3mi/forpca/raw/main/media/logo.png" width="640"> -->

ForPCA is a Fortran library for principal component analysis (PCA).

**fpm Dependency:**
```toml
[dependencies]
forpca = { git = "https://github.com/gha3mi/forpca.git" }
```

## ForEig

[![GitHub](https://img.shields.io/badge/GitHub-ForEig-blue.svg?style=social&logo=github)](https://github.com/gha3mi/foreig)
[![Version](https://img.shields.io/github/release/gha3mi/foreig.svg)](https://github.com/gha3mi/foreig/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/foreig/)
[![License](https://img.shields.io/github/license/gha3mi/foreig?color=green)](https://github.com/gha3mi/foreig/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/foreig/actions/workflows/ci.yml/badge.svg)](https://github.com/gha3mi/foreig/actions/workflows/ci.yml)

<!-- <img alt="ForEig" src="https://github.com/gha3mi/foreig/raw/main/media/logo.png" width="640"> -->

ForEig is a Fortran library for eigenvalue and eigenvector calculations.

**fpm Dependency:**
```toml
[dependencies]
foreig = { git = "https://github.com/gha3mi/foreig.git" }
```

## ForClust

[![GitHub](https://img.shields.io/badge/GitHub-ForClust-blue.svg?style=social&logo=github)](https://github.com/gha3mi/forclust)
[![Version](https://img.shields.io/github/release/gha3mi/forclust.svg)](https://github.com/gha3mi/forclust/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/forclust/)
[![License](https://img.shields.io/github/license/gha3mi/forclust?color=green)](https://github.com/gha3mi/forclust/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/forclust/actions/workflows/ci.yml/badge.svg)](https://github.com/gha3mi/forclust/actions/workflows/ci.yml)

<!-- <img alt="ForClust" src="https://github.com/gha3mi/forclust/raw/main/media/logo.png" width="640"> -->

ForClust allows you to manage and control a Linux system, such as adjusting the settings of the CPU and other components.

**fpm Dependency:**
```toml
[dependencies]
forclust = { git = "https://github.com/gha3mi/forclust.git" }
```

## ForSolver

[![GitHub](https://img.shields.io/badge/GitHub-ForSolver-blue.svg?style=social&logo=github)](https://github.com/gha3mi/forsolver)
[![Version](https://img.shields.io/github/release/gha3mi/forsolver.svg)](https://github.com/gha3mi/forsolver/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/forsolver/)
[![License](https://img.shields.io/github/license/gha3mi/forsolver?color=green)](https://github.com/gha3mi/forsolver/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/forsolver/actions/workflows/ci.yml/badge.svg)](https://github.com/gha3mi/forsolver/actions/workflows/ci.yml)

<!-- <img alt="ForSolver" src="https://github.com/gha3mi/forsolver/raw/main/media/logo.png" width="640"> -->

ForSolver provides linear and nonlinear solvers.

**fpm Dependency:**
```toml
[dependencies]
forsolver = { git = "https://github.com/gha3mi/forsolver.git" }
```

## ForDiff

[![GitHub](https://img.shields.io/badge/GitHub-ForDiff-blue.svg?style=social&logo=github)](https://github.com/gha3mi/fordiff)
[![Version](https://img.shields.io/github/release/gha3mi/fordiff.svg)](https://github.com/gha3mi/fordiff/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/fordiff/)
[![License](https://img.shields.io/github/license/gha3mi/fordiff?color=green)](https://github.com/gha3mi/fordiff/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/fordiff/actions/workflows/ci.yml/badge.svg)](https://github.com/gha3mi/fordiff/actions/workflows/ci.yml)

<!-- <img alt="ForDiff" src="https://github.com/gha3mi/fordiff/raw/main/media/logo.png" width="640"> -->

ForDiff is a Fortran library for numerical differentiation.

**fpm Dependency:**
```toml
[dependencies]
fordiff = { git = "https://github.com/gha3mi/fordiff.git" }
```

## ForTime

[![GitHub](https://img.shields.io/badge/GitHub-ForTime-blue.svg?style=social&logo=github)](https://github.com/gha3mi/fortime)
[![Version](https://img.shields.io/github/release/gha3mi/fortime.svg)](https://github.com/gha3mi/fortime/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/fortime/)
[![License](https://img.shields.io/github/license/gha3mi/fortime?color=green)](https://github.com/gha3mi/fortime/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/fortime/actions/workflows/CI_test.yml/badge.svg)](https://github.com/gha3mi/fortime/actions/workflows/CI_test.yml)

<!-- <img alt="ForTime" src="https://github.com/gha3mi/fortime/raw/main/media/logo.png" width="640"> -->

ForTime is a Fortran library for measuring elapsed time, CPU time, OMP time, and MPI time.

**fpm Dependency:**
```toml
[dependencies]
fortime = { git = "https://github.com/gha3mi/fortime.git" }
```

## ForLapack

[![GitHub](https://img.shields.io/badge/GitHub-ForLapack-blue.svg?style=social&logo=github)](https://github.com/gha3mi/forlapack)
[![Version](https://img.shields.io/github/release/gha3mi/forlapack.svg)](https://github.com/gha3mi/forlapack/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/forlapack/)
[![License](https://img.shields.io/github/license/gha3mi/forlapack?color=green)](https://github.com/gha3mi/forlapack/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/forlapack/actions/workflows/ci.yml/badge.svg)](https://github.com/gha3mi/forlapack/actions/workflows/ci.yml)

<!-- <img alt="ForLapack" src="https://github.com/gha3mi/forlapack/raw/main/media/logo.png" width="640"> -->

ForLAPACK is a Fortran library for LAPACK-related operations.

**fpm Dependency:**
```toml
[dependencies]
forlapack = { git = "https://github.com/gha3mi/forlapack.git" }
```

## ForBlas

[![GitHub](https://img.shields.io/badge/GitHub-ForBlas-blue.svg?style=social&logo=github)](https://github.com/gha3mi/forblas)
[![Version](https://img.shields.io/github/release/gha3mi/forblas.svg)](https://github.com/gha3mi/forblas/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/forblas/)
[![License](https://img.shields.io/github/license/gha3mi/forblas?color=green)](https://github.com/gha3mi/forblas/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/forblas/actions/workflows/ci.yml/badge.svg)](https://github.com/gha3mi/forblas/actions/workflows/ci.yml)

<!-- <img alt="ForBlas" src="https://github.com/gha3mi/forblas/raw/main/media/logo.png" width="640"> -->

ForBLAS is a Fortran library for BLAS-related operations.

**fpm Dependency:**
```toml
[dependencies]
forblas = { git = "https://github.com/gha3mi/forblas.git" }
```

## ForImage

[![GitHub](https://img.shields.io/badge/GitHub-ForImage-blue.svg?style=social&logo=github)](https://github.com/gha3mi/forimage)
[![Version](https://img.shields.io/github/release/gha3mi/forimage.svg)](https://github.com/gha3mi/forimage/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/forimage/)
[![License](https://img.shields.io/github/license/gha3mi/forimage?color=green)](https://github.com/gha3mi/forimage/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/forimage/actions/workflows/CI_test.yml/badge.svg)](https://github.com/gha3mi/forimage/actions/workflows/CI_test.yml)

<!-- <img alt="ForImage" src="https://github.com/gha3mi/forimage/raw/main/media/logo.png" width="640"> -->

ForImage is a Fortran library for PNM file processing and image editing. 

**fpm Dependency:**
```toml
[dependencies]
forimage = { git = "https://github.com/gha3mi/forimage.git" }
```

## ForInv

[![GitHub](https://img.shields.io/badge/GitHub-ForInv-blue.svg?style=social&logo=github)](https://github.com/gha3mi/forinv)
[![Version](https://img.shields.io/github/release/gha3mi/forinv.svg)](https://github.com/gha3mi/forinv/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/forinv/)
[![License](https://img.shields.io/github/license/gha3mi/forinv?color=green)](https://github.com/gha3mi/forinv/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/forinv/actions/workflows/ci.yml/badge.svg)](https://github.com/gha3mi/forinv/actions/workflows/ci.yml)

<!-- <img alt="ForInv" src="https://github.com/gha3mi/forinv/raw/main/media/logo.png" width="640"> -->

ForInv is a Fortran library for calculating pseudoinverse using various methods.

**fpm Dependency:**
```toml
[dependencies]
forinv = { git = "https://github.com/gha3mi/forinv.git" }
```

## ForDebug

[![GitHub](https://img.shields.io/badge/GitHub-ForDebug-blue.svg?style=social&logo=github)](https://github.com/gha3mi/fordebug)
[![Version](https://img.shields.io/github/release/gha3mi/fordebug.svg)](https://github.com/gha3mi/fordebug/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/fordebug/)
[![License](https://img.shields.io/github/license/gha3mi/fordebug?color=green)](https://github.com/gha3mi/fordebug/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/fordebug/actions/workflows/CI_test.yml/badge.svg)](https://github.com/gha3mi/fordebug/actions/workflows/CI_test.yml)

<!-- <img alt="ForDebug" src="https://github.com/gha3mi/fordebug/raw/main/media/logo.png" width="640"> -->

ForDebug is a Fortran library designed for debugging Fortran code, especially within pure procedures.

**fpm Dependency:**
```toml
[dependencies]
fordebug = { git = "https://github.com/gha3mi/fordebug.git" }
```

## ForBenchmark

[![GitHub](https://img.shields.io/badge/GitHub-ForBenchmark-blue.svg?style=social&logo=github)](https://github.com/gha3mi/forbenchmark)
[![Version](https://img.shields.io/github/release/gha3mi/forbenchmark.svg)](https://github.com/gha3mi/forbenchmark/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/forbenchmark/)
[![License](https://img.shields.io/github/license/gha3mi/forbenchmark?color=green)](https://github.com/gha3mi/forbenchmark/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/forbenchmark/actions/workflows/CI_test.yml/badge.svg)](https://github.com/gha3mi/forbenchmark/actions/workflows/CI_test.yml)

<!-- <img alt="ForBenchmark" src="https://github.com/gha3mi/forbenchmark/raw/main/media/logo.png" width="640"> -->

ForBenchmark is a Fortran library for benchmarking (with support for coarrays).

**fpm Dependency:**
```toml
[dependencies]
forbenchmark = { git = "https://github.com/gha3mi/forbenchmark.git" }
```

## ForUnitTest

[![GitHub](https://img.shields.io/badge/GitHub-ForUnitTest-blue.svg?style=social&logo=github)](https://github.com/gha3mi/forunittest)
[![Version](https://img.shields.io/github/release/gha3mi/forunittest.svg)](https://github.com/gha3mi/forunittest/releases/latest)
[![Documentation](https://img.shields.io/badge/ford-Documentation%20-blueviolet.svg)](https://gha3mi.github.io/forunittest/)
[![License](https://img.shields.io/github/license/gha3mi/forunittest?color=green)](https://github.com/gha3mi/forunittest/blob/main/LICENSE)
[![Build](https://github.com/gha3mi/forunittest/actions/workflows/CI_test.yml/badge.svg)](https://github.com/gha3mi/forunittest/actions/workflows/CI_test.yml)

<!-- <img alt="ForUnitTest" src="https://github.com/gha3mi/forunittest/raw/main/media/logo.png" width="640"> -->

ForUnitTest is a Fortran library for unit testing.

**fpm Dependency:**
```toml
[dependencies]
forunittest = { git = "https://github.com/gha3mi/forunittest.git" }
```

