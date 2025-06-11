# k8s_install
k8s


1. 下載shell
mkdir k8s_installer
cd k8s_installer
git clone https://github.com/fish771024/k8s_installer.git

2. 變更sh權限
chmod +x install-k8s.sh

3. 執行sh
./install_k8s_master.sh
./install_k8s_node.sh

4. 防止自動化失敗
kubectl apply -f https://raw.githubusercontent.com/flannel-io/flannel/master/Documentation/kube-flannel.yml