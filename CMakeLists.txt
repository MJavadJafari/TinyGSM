set(SOURCES "src/TinyGsmBattery.tpp" "src/TinyGsmBluetooth.tpp" "src/TinyGsmCalling.tpp" "src/TinyGsmGPRS.tpp" "src/TinyGsmGPS.tpp" "src/TinyGsmGSMLocation.tpp" "src/TinyGsmModem.tpp" "src/TinyGsmNTP.tpp" "src/TinyGsmSMS.tpp" "src/TinyGsmSSL.tpp" "src/TinyGsmTCP.tpp" "src/TinyGsmTemperature.tpp" "src/TinyGsmTime.tpp" "src/TinyGsmWifi.tpp")
set(INCLUDE_DIRS "src")

idf_component_register(
    SRCS ${SOURCES}
    INCLUDE_DIRS ${INCLUDE_DIRS}
    REQUIRES "arduino" "StreamDebugger"
)