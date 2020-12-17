########################
Hosting Quick Start
########################

.. contents:: On This Page
    :depth: 2
    
----------------------------
Notice: Port Forwarding
----------------------------

There are two ways to make a domain accessible from the outside Internet.

1. You may register your domain with the Metaverse server by creating a `Domain ID` in the domain's web panel found at http://localhost:40100/.
2. Alternatively, you can manually open the following ports on your router and firewall:

    * 40100 : (tcp) administration web portal
    * 40102 : (udp) main connection for clients

----------------------------
Windows
----------------------------

1. Download Vircadia (full, not Interface only).
2. Use the `Express` install option, or if you use the `Custom` option ensure that both the `Vircadia Interface` and `Vircadia Sandbox` options are checked. Vircadia Sandbox is the domain server.

.. image:: _images/full-install-components.png

3. In your start menu, search for and run `Vircadia Sandbox`.
4. Go to ``http://localhost:40100/`` in your web browser and complete the wizard to set up your domain. If the server is on a different machine, then replace 'localhost' with its IP address.
5. In your Vircadia Interface, open the `Explore` app and enter `localhost` (or the server's IP address) to get there.

----------------------------
Linux .rpm
----------------------------

1. Open your terminal.
2. Run the following command to download and install the server:

    sudo yum install |serverrpm|

4. Go to ``http://[IP address of your server]:40100/`` in your web browser and complete the wizard to set up your domain.
5. In your Vircadia Interface, open the `Explore` app and enter your server's IP address to get there.

----------------------------
Linux .deb
----------------------------

1. Open your terminal.
2. Run the following command to download the server:

    wget |serverdeb|

3. Then run this command to update and install the server: 

    sudo apt-get update && sudo apt-get install ./|serverdebfile|

4. Go to ``http://[IP address of your server]:40100/`` in your web browser and complete the wizard to set up your domain.
5. In your Vircadia Interface, open the `Explore` app and enter your server's IP address to get there.
