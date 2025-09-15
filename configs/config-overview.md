# Configuration Files

Current server configuration files for documentation and backup purposes.

## Files Overview

### samba.conf
Samba file sharing configuration
- **Share "mother"**: `/srv/samba/madre` - User: madre (Read/Write access)
- **Share "father"**: `/srv/samba/padre` - User: padre (Read/Write access)  
- **Share "romero1"**: `/srv/samba/r1` - User: romero1 (Read/Write access)
- Security: User-level authentication
- Access: Full read/write permissions for valid users
- Status: Configured (3 user shares active)

### network-config  
Network interface configuration
- Interface: Gigabit Ethernet
- IP: DHCP assigned
- Hostname: romser

### ssh-config
SSH server configuration
- Port: 22 (default)
- Authentication: Password-based
- User: romero
- Status: Active for remote administration
