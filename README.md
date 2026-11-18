# netBRS-ad
Active Directory Bloodhound Collector. 

### We use multiple collectors in single bash script 
- souphound
- rusthound
- bloodyad
- bloodhound-python
- net rpc

## Required Tool Installation
```bash
pipx install soaphound-py
pipx install bloodyad
pipx install bloodhound-python
```
```bash
git clone https://github.com/OPENCYBER-FR/RustHound
cd RustHound
cargo build --release
# or debug version
cargo b
```
