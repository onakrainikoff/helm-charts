## onakrainikoff - Helm Charts Repository

### Adding the chart Repository
```
helm repo add onakrainikoff https://onakrainikoff.github.io/helm-charts
helm repo update
```

### Charts list
You can view the full list of charts and versions [here](https://github.com/onakrainikoff/helm-charts/releases)

### Contributing
Feel free to fork our repo and create a pull request with any new features or bug fixes.

### Process to add a chart to the repository
1. Create a branch or fork for your new chart
2. Initialize new chart in the charts directory with helm create mychart or by copying in your work from outside
3. After chart development is done, run (at minimum) helm lint mychart/ to validate yaml and templates
4. Don’t forget to bump your chart version (if needed)
5. Create a pull request with the new chart or updates
6. Once the PR is approved, the automation will publish the chart to our repository
