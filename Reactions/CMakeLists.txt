target_include_directories(${pelephysics_lib_name} PUBLIC $<BUILD_INTERFACE:${CMAKE_CURRENT_LIST_DIR}>)

target_sources(${pelephysics_lib_name}
  PRIVATE
    ReactorArkode.cpp
    ReactorArkode.H
    ReactorBase.H
    ReactorBase.cpp
    ReactorBDF.H
    ReactorBDF.cpp
    ReactorBDFsolver.H
    ReactorCvode.H
    ReactorCvode.cpp
    ReactorCvodeCustomLinSolver.H
    ReactorCvodeCustomLinSolver.cpp
    ReactorCvodeJacobian.H
    ReactorCvodeJacobian.cpp
    ReactorCvodePreconditioner.H
    ReactorCvodePreconditioner.cpp
    ReactorCvodeUtils.H
    ReactorCvodeUtils.cpp
    ReactorNull.H
    ReactorNull.cpp
    ReactorRK64.H
    ReactorRK64.cpp
    ReactorTypes.H
    ReactorUtils.H
    ReactorUtils.cpp
  )
