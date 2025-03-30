# helmcart-demo
how to use helm chart and deploy our local dev
## prerequisite
- install [golang](https://go.dev/doc/install)(required) from package manager or using [gvm](https://github.com/moovweb/gvm)(optional)
- install [kind](https://kind.sigs.k8s.io/docs/user/quick-start/)(required) using `go install sigs.k8s.io/kind@v0.27.0`
- install [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/)(required) using `curl -o /usr/local/bin/kubectl -L "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"`
- install [k9s](https://github.com/derailed/k9s/)(optional) using:
  ```bash
  curl -OL https://github.com/derailed/k9s/releases/download/v0.40.10/k9s_linux_amd64.deb
  apt install -y ./k9s_linux_amd64.deb
  ```
