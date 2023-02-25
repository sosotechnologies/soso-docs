## Install AWS cli
#### https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

## Install Helm
#### https://helm.sh/docs/intro/install/

## install terraform
#### Link: https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli

## Install Git
#### https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

## Install PiP
#### sudo yum install pip
### https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install-linux.html

## install AWS IAM Authenticator
#### https://docs.aws.amazon.com/eks/latest/userguide/install-aws-iam-authenticator.html

## Install Docker
#### https://docs.aws.amazon.com/AmazonECS/latest/developerguide/create-container-image.html

## Install HomeBrew
```
git clone https://github.com/Homebrew/brew ~/.linuxbrew/Homebrew
mkdir ~/.linuxbrew/bin
ln -s ../Homebrew/bin/brew ~/.linuxbrew/bin
eval $(~/.linuxbrew/bin/brew shellenv)
brew --version
```

## Install Kubectl
#### https://docs.aws.amazon.com/eks/latest/userguide/install-kubectl.html
```
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
curl -LO "https://dl.k8s.io/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl.sha256"
echo "$(<kubectl.sha256)  kubectl" | sha256sum --check
sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
kubectl version --client --output=yaml
```

## Install kubectx/Kubens
#### https://github.com/ahmetb/kubectx#kubectl-plugins-macos-and-linux
```
sudo git clone https://github.com/ahmetb/kubectx /opt/kubectx
sudo ln -s /opt/kubectx/kubectx /usr/local/bin/kubectx
sudo ln -s /opt/kubectx/kubens /usr/local/bin/kubens
```

## [Optional] Install K9s
####  brew install derailed/k9s/k9s


## [Optional] Install CurL
```
sudo yum update
sudo yum install php-curl
curl -V
``` 