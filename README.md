# loukingle.github.io

Hosts the public key for my Tesla Fleet API app (used by Home Assistant).

- `.well-known/appspecific/com.tesla.3p.public-key.pem` — the **public** key.
  Home Assistant creates the key pair during Tesla Fleet setup and shows the
  public half; paste it here, replacing the whole file. The private key stays
  in Home Assistant and never goes in this repository.
- `.nojekyll` — tells GitHub Pages to publish the hidden `.well-known` folder.

Served at https://loukingle.github.io/.well-known/appspecific/com.tesla.3p.public-key.pem
