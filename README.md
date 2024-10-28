jenkins-app-chart
This Helm chart deploys the Jenkins application on a EKS Cluster
Prerequisites:

EKS Cluster (AWS) : must be set up first
Helm must be created with the "helm create repo"


Installing the Chart
To install the chart with the release name : jenkins-app-release


helm install jenkins-app-release  ./cms-app-chart




Upgrading your Chart
To upgrade the chart with the release name : jenkins-app-release


helm upgrade jenkins-app-release  ./cms-app-chart




Installing the Chart with values.yaml
To install the chart with the release name : jenkins-app-release


helm install jenkins-app-release ./cms-app-chart  --Values ./cms-app-chart/values.yaml





Uninstalling the Chart
To uninstall the jenkins-app-release deployment:


helm uninstall jenkins-app-release ./cms-app-chart 
