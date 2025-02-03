# pressure_tester_ota
Repo to update pressure tester 

# Notes Application SW / FW
Remeber to update the correct version, correct WiFi & credentials - do not change the path json_url

const char* version = "2.3";  // ESP32's nuværende version
const char* json_url = "https://raw.githubusercontent.com/ashImbox/pressure_tester_ota/main/firmware.json";  // Rå URL til JSON fil

const char* ssid = "Imbox_Udvikling";
const char* password = "1470014700";


# Notes firmware.json 
This points at the right address and page. Only change version, but remember to do so in both "version" and "bin_url"
{
  "version": "2.3",
  "bin_url": "https://github.com/ashImbox/pressure_tester_ota/releases/download/v2.3/OTA_test.ino.bin"
}

# Notes tags
Under releases press "Draft a new release".
Choose tag, and remember to change the version eg. v2.1
upload bin file named XX.ino.bin to binaries 

When

