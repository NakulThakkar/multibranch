pipeline {
   agent any

   stages {
      stage('1') {
         steps {
            echo 'Hello World'
            echo env.BRANCH_NAME
            echo env.CHANGE_ID
            echo env.CHANGE_URL
            echo env.CHANGE_TITLE
            echo env.CHANGE_AUTHOR
            echo env.CHANGE_AUTHOR_DISPLAY_NAME
            echo env.CHANGE_AUTHOR_EMAIL
            echo env.CHANGE_TARGET
            echo env.CHANGE_BRANCH
            echo env.BUILD_NUMBER
            echo env.BUILD_ID
            echo env.BUILD_DISPLAY_NAME
            echo env.JOB_NAME
            echo env.JOB_BASE_NAME
                        echo env.BUILD_TAG
            echo env.EXECUTOR_NUMBER
            echo env.NODE_NAME
            echo env.NODE_LABELS
            echo env.WORKSPACE
            echo env.JENKINS_HOME
            echo env.JENKINS_URL
            echo env.BUILD_URL
            echo env.JOB_URL
            echo env.GIT_COMMIT
            echo env.GIT_PREVIOUS_COMMIT
            echo env.GIT_BRANCH
            echo env.GIT_CHECKOUT_DIR
         }
      }
   }
}
