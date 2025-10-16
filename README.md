# Virtualization
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
  Machine with Internet access
  Minimum 4 GB RAM
  Sufficient storage space
## Steps:
```
 1.Download Oracle VM VirtualBox:
   1. Visit Oracle VirtualBox Official Site
   2. Download installer for your OS (Windows/macOS/Linux).

 2.Install Oracle VM VirtualBox (Example: Windows):
    1.Launch Installer → Allow Changes → Click Next.
    2.Choose Installation Options → Click Next.
    3.Accept Network Interface Warning → Click Yes.
    4.Click Install.
    5.Finish Installation and Launch VirtualBox.
    
 3.Configure VirtualBox:
    1.Open VirtualBox.
    2.Click New → Name VM → Select Type (Linux/Windows) and Version.
    3.Allocate:
      1.Minimum 2 GB RAM
      2.Create Virtual Hard Disk (20 GB recommended).
    4.Start Virtual Machine and provide ISO to install OS.
```
## Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux

## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
Oracle VM VirtualBox Installed
4 GB RAM and 20 GB Storage Minimum
Kali Linux ISO image

## Steps:
```
1.Download Kali Linux ISO:
   Visit Kali Linux Official Site
   Download 64-bit ISO (Installer version).
2.Create a New Virtual Machine:
   Open VirtualBox → Click New.
   Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
3.Allocate Memory:
   Minimum 2 GB RAM (recommended 4 GB).
   Create Virtual Hard Disk:
   Select VDI (VirtualBox Disk Image).
   Choose Dynamically allocated.
   Set Disk size to 20 GB or more.
4.Configure ISO Image:
  Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
5.Start Installation:
   Boot Virtual Machine → Choose Graphical Install.
   Set Language, Region, Keyboard.
   Configure Network → Set Hostname (e.g., kali).
   Set root password.
   Disk Partitioning: Use entire disk → All files in one partition.
   Install System → Install GRUB Bootloader → Finish Installation.
6.Login to Kali Linux:
   Use root credentials.
7.(Optional) Install Guest Additions:
   Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
```
## snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox
<img width="1603" height="974" alt="image" src="https://github.com/user-attachments/assets/8f79af99-f941-4622-b694-1170135d1c4e" />

Snapshot 2: Kali Running in Virtual
<img width="1919" height="999" alt="image" src="https://github.com/user-attachments/assets/d3df8495-2101-4a25-b464-4a96b3a0b827" />

## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
About Linux:
   Open-source operating system.
   Kernel manages communication between hardware and software.
   Commands are case-sensitive.
## Linux Commands:
1.ls Command
     The ls command is used to display a list of content of a directory.

Syntax:
ls
<img width="714" height="70" alt="image" src="https://github.com/user-attachments/assets/27b1434f-a04f-4fa3-8365-3a7d604176ef" />

2.pwd Command

The pwd command is used to display the location of the current working directory.

Syntax:
pwd
<img width="193" height="67" alt="image" src="https://github.com/user-attachments/assets/128ab04e-e7d1-42bb-9755-70b5205d0cd0" />

3.mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax:
mkdir <directory_name>
<img width="364" height="49" alt="image" src="https://github.com/user-attachments/assets/a577d774-baaf-4cb7-905f-4f9a52ddde15" />

4.rmdir Command

The rmdir command is used to delete a directory.

Syntax:
rmdir <directory_name>
<img width="308" height="50" alt="image" src="https://github.com/user-attachments/assets/9123c0ca-23c0-49f4-bd51-9af6ae953f25" />

5.cd Command The cd command is used to change the current directory
Syntax:
cd <directory_name>


<img width="223" height="42" alt="image" src="https://github.com/user-attachments/assets/6d37a696-2f3d-4fdc-b19d-6e4c63d3d31c" />


6.cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

Syntax:
cat [options] [file_name]

<img width="632" height="73" alt="image" src="https://github.com/user-attachments/assets/20d77b76-ce6c-4c48-9548-1a1d8678d373" />

<img width="866" height="71" alt="image" src="https://github.com/user-attachments/assets/56a06f8d-c225-4d29-b41b-7c8b09752309" />
7.cp Command

The cp command is used to copy a file or directory.

Syntax:
cp [source] [destination]

<img width="300" height="52" alt="image" src="https://github.com/user-attachments/assets/9195f238-958e-43ae-83a0-ba327401a4d2" />

<img width="831" height="62" alt="image" src="https://github.com/user-attachments/assets/f7ae810f-b253-4349-b051-b11e03122dd7" />

8.mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax:
mv [source] [destination]

<img width="293" height="52" alt="image" src="https://github.com/user-attachments/assets/e2671a91-7181-4a44-96d9-b0735d3b47a9" />

<img width="339" height="64" alt="image" src="https://github.com/user-attachments/assets/a15ee6ba-c584-4f6b-bdb5-6b1297440905" />

9.touch Command

Create empty file.

Syntax:
touch [filename]

<img width="185" height="44" alt="image" src="https://github.com/user-attachments/assets/2509c845-1a9f-40a6-9487-1396de2a0b64" />

10.vi Command

Edit file contents using editor.

Syntax:
vi [filename]

<img width="192" height="51" alt="image" src="https://github.com/user-attachments/assets/4394bd5a-31e7-4ff8-a342-56a523c706ca" />

## Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.
