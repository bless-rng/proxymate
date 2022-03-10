Linux proxy docker service

How to use.
1. Create new config file like example.com for your service (myservice.conf).
2. Configure server_name and ports, proxy_pass, redirects, servers and something else what you need with open ports. 
3. Add to hosts your new server_name <pre>
    127.0.0.1       myserver.com
    127.0.0.1       api.myserver.com
    </pre>
4. Restart service `docker-compose up -d`
5. Use. Now you can use human readable url for your services.
