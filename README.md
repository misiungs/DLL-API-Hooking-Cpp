# DLL-API-Hooking-Cpp 
API Hooking implemented in DLL for injection purposes. <br/>
DLL when injected into a process performs API Hooking of MessageBoxA with trampoline. <br/>
The hooked function extracts MessageBoxA function parameters through base64-encoded query parameters in HTTP GET requests to domain of choice.<br/>
