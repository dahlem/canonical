# Copyright (C) 2007-2013 Dominik Dahlem <Dominik.Dahlem@gmail.com>
#  
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without 
# modifications, as long as this notice is preserved.
# 
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

AC_PREREQ(2.61)
AC_INIT([Canonical Analysis],
        [2.0],
        [Dominik Dahlem Dominik.Dahlem@gmail.com], 
        [canonical])

AM_INIT_AUTOMAKE

AC_CONFIG_FILES([
   DESCRIPTION
   Makefile
   inst/backscale_design.m
   inst/ca_analyseRidgeFocal.m
   inst/ca_analyseRidgeFocalIntermediate.m
   inst/ca_coeffM.m
   inst/ca_coord1.m
   inst/ca_eigNorm.m
   inst/ca_eigNormM.m
   inst/ca_lse.m
   inst/ca_mesh.m
   inst/ca_mesh2D.m
   inst/ca_meshSobol.m
   inst/ca_modelM.m
   inst/ca_modelW.m
   inst/ca_modelWM.m
   inst/ca_modelX.m
   inst/ca_modelXM.m
   inst/ca_reducedModel.m
   inst/ca_ridgeAnalysis.m
   inst/ca_ridgeAnalysisWithFocal.m
   inst/ca_serialiseEigen.m
   inst/ca_serialiseModel.m
   inst/ca_serialiseRidge.m
   inst/ca_serialiseStatP.m
   inst/ca_sndOrderModel.m
   inst/ca_sndOrderModel1.m
   inst/ca_statX.m
   inst/ca_w.m
   inst/gen3fact.m
   inst/scale_design.m
])


AC_OUTPUT

for top_builddir in . .. ../.. $ac_auxdir $ac_auxdir/..; do
  test -f $top_builddir/configure && break
done

AC_MSG_RESULT([

$PACKAGE $VERSION: Automatic configuration OK.

])
