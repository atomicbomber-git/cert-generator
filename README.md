An `expect` script to generate a self-signed SSL certificate. Requires the GNU `expect` program to be installed.


Can be used to allow HTTPS for sites that are served locally, by adding the generated .pem file into the browser's list of trusted
certificate Authorities.


Usage example:
```bash
# Make the script executable in case it isn't yet
chmod +x generate.exp

# Run the script and check the script's directory for all the files that are generated
./generate.exp
```
