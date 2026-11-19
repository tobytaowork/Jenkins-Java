
/**
 * Java 项目 Jenkins 流水线
 *
 * 引用公共项目 Jenkins-Common
 */
@Library('Jenkins-Common') _

pipeline {
    agent any

    stages {

        stage('测试公共步骤') {
            steps {
                script {

                    // 调用 Jenkins-Common 公共项目中的打印方法
                    printMessage('Java 项目调用公共步骤成功！')

                }
            }
        }

    }
}
