# ERRORS
## DOCKER HOST
### ISSUE
vm.max_map_count [65530] is too low, increase to at least [262144]
### SOLVED WITH
sudo sysctl -w vm.max_map_count=262144
