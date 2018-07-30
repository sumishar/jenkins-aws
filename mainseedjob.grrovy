categorizedJobsView('Main'){
  jobs {
    //regex(/^.*$/)
    regex(/^((?!MainSeedJob).)*$/)
  }
  categorizationCriteria {
    regexGroupingRule(/^.*.general$/, 'General: Stack')
  }
 

  columns {
    status()
    weather()
    name()
    lastSuccess()
    lastFailure()
    lastDuration()
    buildButton()
  }
}

categorizedJobsView('DSL'){
  jobs {
    regex(/^.*_groovy$/)
  }
  columns {
    status()
    weather()
    name()
    lastSuccess()
    lastFailure()
    lastDuration()
    buildButton()
  }
}

categorizedJobsView('Z-store'){
  jobs {
    regex(/^.*_z$/)
  }
  categorizationCriteria {
    regexGroupingRule(/^.*.dev_z$/, 'SandBox')
  }
  categorizationCriteria {
    regexGroupingRule(/^.*.prd_z$/, 'Just Convert THIS!!!')
  }
  columns {
    status()
    weather()
    name()
    lastSuccess()
    lastFailure()
    lastDuration()
    buildButton()
  }
}
