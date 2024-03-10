# Bank-Management

git@github.com:wkhaliddev/Bank-Management.git


In this project there a three basic portions:
1-admin
2-customer
3-staff
so all these have different levels of authorizations like 

1-customer can :
perform transaction and like that

3-staff can:
add amount in account
deduct amount from account
request to open account

3-admin can:
see all accounts 
can read all accounts
can give permission to open account
have cresidentials of all accounts


# Write a CMakeList for an open-source C++ project of your choice, containing multiple *.h and *.cpp sourse files.

### Get the up-to-date list of packages available for the installation by running the following command:
sudo apt update -y

### Run the following command to install the cross-compilation tools:
sudo apt install -y crossbuild-essential-armel

### go to the build directory
cd build


# Compile for x86 architecture
## Commit 16-21 lines in CMakeLists.txt
### Run CMake:
**cmake ..**

### Now, build the application by running the following:
make

### Get information about the resulting executable binary using the file command:
file hello


# Compile for ARM architecture
## UnCommit 16-21 lines in CMakeLists.txt
### Remove files in folder
rm -rf ./*

### Run CMake:
cmake ..

### Now, build the application by running the following:
make

### Get information about the resulting executable binary using the file command:
file hello
