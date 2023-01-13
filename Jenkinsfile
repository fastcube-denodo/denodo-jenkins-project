node {
    checkout([
        $class: 'GitSCM',
        branches: [[name: ${commitId}]],
        doGenerateSubmoduleConfigurations: false,
        extensions: [],
        submoduleCfg: [],
        userRemoteConfigs: [[url: ${gitUrl}]]])
    sh 'ls -al'
}
