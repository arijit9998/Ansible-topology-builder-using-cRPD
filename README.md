# Ansible-topology-builder-using-cRPD
Ansible script to bring up topology in cRPD 


- Can provision any number of servers hosting cRPD
- Can bring up and connect any number of cRPD containers per server
- User can attach any number of interfaces per container
- It takes care of underlying networking plumbing as per the topology specified by user.
- Topology can span across any number of physical servers.
 
All underlying complexities are hidden from user and everything specified above can be accomplished by user supplied topology input in the YAML file.
