# mosquitto_tls
<br>
A Mosquito server compiled with TLS support and configurable self signed certificates generated at build time.
<br>


[![](https://images.microbadger.com/badges/version/krital/mosquitto_tls.svg)](https://microbadger.com/images/krital/mosquitto_tls "Get your own version badge on microbadger.com")

The following is configured through environment variables with the following defaults:
<br><br>
MOSQUITTO_PORT="8883" <br>
MOSQUITTO_SOURCE_DIR="/usr/local/src" <br>
MOSQUITTO_CONFIG_DIR="/etc/mosquitto" <br>
MOSQUITTO_VERSION="1.4.8" <br>
MOSQUITTO_USER="mosquitto" <br>
CERTIFICATE_DURATION="365" <br>
CA_FILE_PREFIX="ca" <br>
CA_KEY_PASSWORD="capasswd" <br>
CA_COUNTRY="GR" <br>
CA_STATE="Attica" <br>
CA_LOCALITY="Athens" <br>
CA_ORGANIZATION="SYRIZA" <br>
CA_COMMON_NAME="SYRIZA CA" <br>
SERVER_FILE_PREFIX="server" <br>
SERVER_KEY_SIZE="2048" <br>
SERVER_KEY_PASSWORD="serverpasswd" <br>
SERVER_COUNTRY="GR" <br>
SERVER_STATE="Attica" <br>
SERVER_LOCALITY="Athens" <br>
SERVER_ORGANIZATION="kritikal.org" <br>
SERVER_DOMAIN="mosquitto.kritikal.org" <br>
SERVER_COMMON_NAME="test.$SERVER_DOMAIN" <br>
ROOT_PASSWORD="Mosquitto!"<br>

<br>
