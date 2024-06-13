# opentofu-proxmox
Proxmox Opentofu 


# Opentofu Yüklemek
```bash
sudo apt update
sudo apt install opentofu
```

# Tofu Plugins Yüklenmesi
```bash
mkdir -p ~/.terraform.d/plugins
cd ~/.terraform.d/plugins
git clone https://github.com/bpg/terraform-provider-proxmox.git
```

# Tofu Komutları
```bash
tofu init # Tofu konfigürasyonunu oluşturur
tofu apply # VM Oluşturur
tofu destroy # Oluşturulan VM siler
```