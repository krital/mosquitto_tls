# mosquitto_tls
A Mosquito server compiled with TLS support and configurable self signed certificates generated at build time.

The following is configured through environment variables with the following defaults:

MOSQUITTO_PORT="8883" 
MOSQUITTO_SOURCE_DIR="/usr/local/src" 
MOSQUITTO_CONFIG_DIR="/etc/mosquitto" 
MOSQUITTO_VERSION="1.4.8" 
MOSQUITTO_USER="mosquitto" 
CERTIFICATE_DURATION="365"
CA_FILE_PREFIX="ca" 
CA_KEY_PASSWORD="capasswd" 
CA_COUNTRY="GR" 
CA_STATE="Attica" 
CA_LOCALITY="Athens" 
CA_ORGANIZATION="SYRIZA" 
CA_COMMON_NAME="SYRIZA CA"
SERVER_FILE_PREFIX="server" 
SERVER_KEY_SIZE="2048" 
SERVER_KEY_PASSWORD="serverpasswd" 
SERVER_COUNTRY="GR" 
SERVER_STATE="Attica" 
SERVER_LOCALITY="Athens" 
SERVER_ORGANIZATION="kritikal.org" 
SERVER_DOMAIN="mosquitto.kritikal.org" 
SERVER_COMMON_NAME="test.$SERVER_DOMAIN"
ROOT_PASSWORD="Mosquitto!"
