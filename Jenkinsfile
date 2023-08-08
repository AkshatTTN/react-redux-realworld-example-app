@Library('git-shared-lib') _
ReactBuildEcsDeploy([ 
 appName: 'react-img',
 dockerFilePath: 'Dockerfile',
 master: [
     scriptToRun: '''
       whoami
       ls -la
       ''',
     containerRegistoryUrl: '919678485989.dkr.ecr.ap-south-1.amazonaws.com',
     clusterName: 'jen-cluster',
     nodeVersion: '16.20.0',
     serviceName: 'demo-svc1',
     taskDefinition: 'demo-task1',
     notification: [
      [
        type: 'email',
        fromAddress: 'sanchi.sharma1@tothenew.com',
        toAddress: 'akshat.mittal@tothenew.com'
      ]
    ]
]
])
//ReactBuildEcsDeploy()
