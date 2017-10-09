上传命令：
gradlew install
gradlew bintrayUpload

或者下面一行命令即可：
gradlew clean build bintrayUpload -PbintrayUser=zhoulc668 -PbintrayKey=******************** -PdryRun=false