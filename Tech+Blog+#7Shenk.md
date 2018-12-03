#*CIS 141*
##**Anthony Shenk**

* Love to work with computer hardware
* I wake up early
* Have taken ICT in high school
* Plan on Majoring in Network Security
* Have 5 Siblings
* I tend to do things last minute

  I am Anthony Shenk, I was born August 4th 2000. I've always loved video games and computers, especially the hardware side of things.
I've always enjoyed the software side of things but found it much harder to self teach it. I took lots of tech classes at my High school in Lincoln, 
finishing most of the IT classes they had to offer. I always tended to get good grades on the assignments I actually tried to do, 
but I rarely actually tried to do my work due to me being lazy.

**Warm Up 8-27**

If I had to guess how many computers I would say in the ball park of 60 to 70 computers are in this room. There is 32
desktops, around 30 people that I'm guessing each have a phone, and probably a few laptops averaging out to about 60
to 70 computers.

**8-27 Notes**
Requirements
Edition(Home, Pro ,Enterprise, Mobile, Mobile Enterprise, Education, IOT Core, S)
Create media



Provision Upgrade Turns device into Enterprise device.


**Warm Up 9-10**

Microsoft released an application on android devices called "Your Phone".It allows for a user to connect their phone and pc
together (as long as the Pc runs Windows 10) so that they can access their text and photos.

Microsoft also came out and said that they will continue to protect and update you Windows 7 Pc as long as you pay a
monthly fee that will increase in price every year until the year 2023 when even this support will end.

Citation - 

 [Microsoft Releases New Application Your Phone](https://9to5google.com/2018/09/10/your-phone-app-windows-10-android/)
	
   [Windows 7 Support](https://www.forbes.com/sites/gordonkelly/2018/09/08/microsoft-windows-7-monthly-charge-windows-10-free-upgrade-cost/#6e39606e2db1)

**Skill 1.2**

1. Why need partitions and how to create? - To have sections reserved for certain things such as a partition only for the OS. 
Open disk management, right click on drive and shrink drive to set size. the right click on partition and change drive/partition letter

2. Attention Needed at/during? - Installation Key when typing in key, Disk Partition when setting up/formatting drives

3. I added Hyper V and removed Internet Explorer, I did this through optional features which you can launch by 
Windows Key + R then type Optionalfeatures.exe then select/deselect features as needed. 


**Warm Up 9-17**

Patch Tuesday (Update Tuesday) occurs on the second, and sometimes fourth, Tuesday of each month in North America. As far as the 
integrated Windows Update (WU) function is concerned, Patch Tuesday begins at 10:00pm PST. Last occuring September 11th 2018, it fixed Edge and 
internet explorer vulnerability. 

**Skill 1.2 Windows 10 Upgrade **

1.  WinAmp may not be compatible due to its encoding method for videos.
2. My Txt File says Real Estate Office and its on my desktop
3. Select don't upgrade,  Sign life away, WAIT FOREVER,
4. Lots of waiting and accepting terms.
5. Windows Old folder in C: Drive. The ability to revert to 


**Skill 1.3**
1. USB, Audio Devices, Printer, Mice, Keyboards, Computers parts (GPU, Motherbaords Etc) 
2. Headset
3. It is most up to date
4. Disabling it didn't affect performance, but early this year this driver actually caused
my PC to blue screen.
5. So you don't use all your data. I couldnt get to this screen because there is no Wifi Option,
However I jsut showed use VPN on metered connections, 
6. I went to their website and downlaoded an older driver. No issues arouse
7. By unplugging the USB Mic, uninstalling the driver and then restarting the
Pc and testing the performance.

**Warm Up 9-24**
I don't think that the future of operating systems lays in the cloud, at least for desktops and possibly laptops. Tablets and some laptops
may be using this method in the future exclusively. 

**SKILL 1.4**
**Power Settings**

- Search Bar
- Search Power Config
- Press Enter
- Select and configure the settings to your liking

**Hyper V**
- Press windows key + R
-type "optionalfeatures.exe" and hit enter
- Check Hyper V
- Reboot
- In search bar type "Hyper V"
- Boot Hyper V and select a ISO file to boot a Virtual machine up

**Warm up 10-1-18**

UAC was introduced in Windows Vista and Windows Server 2008. UAC on my VM vs MYSierra machine isn't that diffrent, the only thing I can't do is run
some programs as an Admin.

**Skill 1.5**

LSDO

- L: Local

Can control User and computer settings, Control and Deployment of applications, and control user experience 

- S: Site many local machines

- D: Domain many sites

- O: Organizational Units king of permissions

1: 

2: Pin Complexity you can make a pin 4 to 127 characters required

3: You can block Microsoft accounts through the option, Block Microsoft User Accounts


**Skill 2.1**

1. Accounts- Make sure you have a password on your account. Event Logging enabled
2. Manage cleint computers on your domain through group policy
3. NPS- Restrict websites and network traffic.
4. Use Ipsec- Use to encrypt data over the network.
5. Authentication- Use PEAP for strong authentication. 

**Skill 2.2**

1. I would create a Storage space with all the drives
2.  You could create a Raid 1 or Raid 0 volume


**Skill 2.4**
1. To give all machines Microsoft office you can just manulaly send out the application 
through the microsoft deployment kit without much thought.
2.Deploying ADobe and Quickbooks to specfic computers is a little diffrent, you need to have those machines set up as diffrent departments
then rould out the programs to each type of machine that needs it. Adobe Acrobat will probabaly be best rolled out if you just
gave out the installer and let the use decide if they want to install it.


**Skill 2.5**
1. The Firewall is blocking the RDP port
2. There are a few good ways to help all the users, one would be to have a basic tech course that informs users of basic issues so that they can trouble shoot
some of the basic problems themselves, another decent way to help everyone would be to set up a basic "ticket" system where people report their issue then
send it into the support staff where they can try to help via email. This would allow a staff member to help multiple people within a shorter amount of time rather 
than having to visit each person to help.

**Skill 3.1**
1. I would create two machines one which I would update and one I would keep one version so I could refer back to what works and what doesn't work on certain updates.
However you could create a single machine with flash back points to roll back to for the previous update.
2. I would recomend Enterprise LTSC because it because it recieves little to no updates, and doesn't come with unecsarry features like Microsoft Store and some bundled apps.
3. I would use Applocker to lock out the microsoft store to users so they couldn't even use it in the first place.


**Skill 3.1/3.2**
1. You could simple tools like task manager to monitor a systems Ram, Disk, Cpu and Network usage to see if a certain system component simply can't handle a load of the newer OS and the applications,
or if the application is simply not optimized for the OS. There are other tools such as HWMonitor that allow you to monitor similar variables but more in depth. 
2. I would periodically create a restore point, so that if something were to happen to my system I could just reload to the latest restore point. If I was trying to prevent
the loss of files even if I lost my laptop I would back them up on the cloud, and if neither of these options were open to me I would simply have a backup  external hard drive that I saved
files to when needed. 