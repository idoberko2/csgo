Step by step
===

1. Create a 20$ droplet with 4GB RAM and 80GB Disk
2. Copy one of the `docker-compose.yml` files to the droplet
3. Add the missing values
4. Run `docker-compose up -d`
5. Open ports:
    1. Run `sudo ufw allow 27015/tcp`
    2. Run `sudo ufw allow 27015/udp`
6. Verify they're open by running: `lsof -i :27015`
