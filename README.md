# Setting Up & Configuring Pfsense on VM - Lab
<img src="https://img.shields.io/badge/-pfSense%20Firewall-blue?style=for-the-badge"></img>

## Objective
This lab includes steps for setting up  pfsense firewall in a VM for leanring and educational purpose .

### Skills Learned

- Configure Pfsenser firewall
- Create basic rules
### Installting OFsense on VM Refer to <a href="https://github.com/syedhnaqvi/pfsense">Installing Pfsense on VM</a>

### Diagram Ref...
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/4cd7959e-8ed5-4229-983b-cd60abe985a2)

<b> OPT interface in Pfsense stands fro Optionsl Interface it enables you to create different interface on pfsense for multiple purposes. Can be used for different network / segments like IOT devices , guest network etc.</b>
### Step -1 
User Ubuntu VM to connect to LAN 192.168.1.1 from Browser using credential username : admin Password:pfsense
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/2beeaaad-598d-4904-b40f-bfc9962d49e3)

Choose Setup Wizard and click NEXT to proceed
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/e59705ef-3cbe-4791-8cb9-21197d2c2115)

Click NEXT again !
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/c19fbaf8-842b-456e-8ad5-19706a5b0f2c)

Choose any hostname : that be used to access instead fo using IP address will leave default values for hostname and for domain use any FQDN .
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/8b7be1aa-69cf-40b7-bda3-db79cc47c7c3)

Type in Primary and sec DNS if you dont have any specific ones user Google DNS .
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/15bee9ef-68fa-4969-810d-55785be1b90d)

Select your time zone .
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/29bb1003-9505-424c-97ce-ca8efbc7164b)

Next Screen User DHSCP for SOHO /Home settings and click NEXT.
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/51318990-5460-4314-a7d2-3ff8a963fb10)

Use default unitl & unless need to modify.
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/f845c7a2-22c2-4518-8aa6-a3dcbdb4c2fa)

Chnage AMDIN password for GUI and user strong password .
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/cb2e6656-af97-44c1-a0c2-9ac3ca555c7b)

Click RELOAD button
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/e8b4e688-70b6-4303-a142-596cdd187a44)

Click FINISH to complete & Exit Wizard
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/0e7a23a7-c631-441f-aeab-fb2a3a79c2d8)

If need to chnage DHSCP Server settings go to Services>DHCP Server 
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/9b315254-a69c-4cf3-90be-fbf9cb472b80)

Disallow Browser to save ADMIN credentails.
![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/eccc4bb4-2858-4d8c-b189-46ef3b123fc4)

![image](https://github.com/syedhnaqvi/pfsense-setup-config/assets/39069507/5cd15784-b48f-4a83-a1cb-8ad46f3758f2)


### Reference 
<a href="https://www.youtube.com/watch?v=QUoBpoFO_Yc">Setup Pfsense- Video</a>

