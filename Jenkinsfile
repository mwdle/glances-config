boolean disableIndexTriggers = env.BRANCH_NAME != 'main'

quadletPipeline(
    disableIndexTriggers: disableIndexTriggers,
    podmanSecretMappings: [
        [
            type: 'string',
            credentialsId: 'glances-password-file',
            podmanSecretStringName: 'glances_password_file'
        ]
    ]
)
