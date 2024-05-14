option(BUILD_ExtExampleCmdApps "Build command-line apps for the Example module" ON)

if(BUILD_ExtExampleCmdApps)
  mitkFunctionCreateCommandLineApp(
    NAME ExampleCmdApp2
    DEPENDS MitkExampleModule2
  )
endif()
