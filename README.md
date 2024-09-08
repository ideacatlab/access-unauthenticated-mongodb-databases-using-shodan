# Accessing Unauthenticated MongoDB Databases Using Shodan

## 1. Install MongoDB Compass
- Download and install MongoDB Compass.

## 2. Search for Vulnerable Servers Using Shodan
- Use the Shodan dork:
"MongoDB Server Information" port:27017 -authentication

- Port Mostly used:
  ```
  27017
  27018
  27019
  ```

## 3. Connect to the Vulnerable Server
- Run the command:

`mongosh mongodb://<IP>:27017`

- Replace `<IP>` with the IP address of the vulnerable server found via Shodan.

## 4. Explore the Database
- Use the command:


- List the databases on the connected server.

## 5. Report the Misconfiguration to the Site owner
