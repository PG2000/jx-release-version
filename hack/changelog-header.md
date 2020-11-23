### Linux

```shell
curl -L https://github.com/jenkins-x-plugins/jx-release-version/releases/download/v{{.Version}}/jx-release-version-linux-amd64.tar.gz | tar xzv 
sudo mv jx-release-version /usr/local/bin
```

### macOS

```shell
curl -L  https://github.com/jenkins-x-plugins/jx-release-version/releases/download/v{{.Version}}/jx-release-version-darwin-amd64.tar.gz | tar xzv
sudo mv jx-release-version /usr/local/bin
```

