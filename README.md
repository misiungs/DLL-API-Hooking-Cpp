# DLL-API-Hooking-Cpp
API Hooking implemented in DLL for injection purposes.
DLL when injected into process performs API Hooking of MessageBoxA with trampoline.
The hooked function extracts function parameters through base64-encoded query parameters in HTTP GET requests.
