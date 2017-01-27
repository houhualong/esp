## EXAMPLES

The examples show you how to use LuaNode.

* `wifi_scan`: Scan all APs around ESP32 device.
* `raw_flash_rw`: Read write ESP32 flash directly without file system.
* `simple_http_server`: Create a simple http server on ESP32. To test this 
			example, build it follow the next section, and then 
			connect to the AP established on ESP32 using your phone. 
			The AP named as `DOIT_XXXX`. When connect to ESP32 device, 
			open `192.168.4.1` on browser, you'll see a test page, 
			which echo `This is a test`, returned 
			from ESP32.
* `dns_resolver`: A DNS resolver sample. To test this sample, connect your phone or 
		computer to ESP32 which run this sample, and then open any link in the browser.
		the return page will be a test page.

## HOW TO BUILD THE EXAMPLES

Copy the app_main.c within each example to the `main` folder within LuaNode32,
and then run `./build.sh` to build LuaNode.