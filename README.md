# STM32_LoRaWan

// Pin mapping
const lmic_pinmap lmic_pins = {
  .nss = PB12,
  .rxtx = LMIC_UNUSED_PIN,
  .rst = PA8,
  .dio = {PB1, PB10, PB11}
};

