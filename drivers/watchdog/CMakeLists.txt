zephyr_sources_ifdef(CONFIG_WDT_QMSI wdt_qmsi.c)
zephyr_sources_ifdef(CONFIG_IWDG_STM32 iwdg_stm32.c)
zephyr_sources_ifdef(CONFIG_WDOG_CMSDK_APB wdog_cmsdk_apb.c)
zephyr_sources_ifdef(CONFIG_WDT_SAM wdt_sam.c)
zephyr_sources_ifdef(CONFIG_WDT_ESP32 wdt_esp32.c)
