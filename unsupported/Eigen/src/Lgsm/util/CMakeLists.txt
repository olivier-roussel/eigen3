FILE(GLOB Eigen_Lgsm_util_SRCS "*.h")

INSTALL(FILES
  ${Eigen_Lgsm_util_SRCS}
  DESTINATION ${INCLUDE_INSTALL_DIR}/unsupported/Eigen/src/Lgsm/util COMPONENT Devel
  )
