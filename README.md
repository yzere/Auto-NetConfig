# Auto-NetConfig
Automatic network configuration application to save your time.

# Core concepts

- Provide topology choice
- Provide subneting 
- Provide logical adressing for devices
- Show visual representation of topology
- Show visual representation of logical adressing
- Give hint for Cisco CLI command under given functionalities
- Solve simple problems with net-config

# Core functionalities

- Choose device type
- Ask for subneting and provide such option
- Show proces of subneting and representative table
- Generate manual step-by-step for device configuration
- Show alternative options in manual


# Build plan

## Part 1: Providing basic information

### Details to provide:
- Number of devices
- Connections to establish
- Ports availible
- Base network and subneting options
- Graphical description of subneting ranges

## Part 2: Config

Choose whether to configure devices or to solve problems.

### 2.1 Choosing config options

#### Choose connections and configure

- Choose connection to establish
- Choose ports to connect with
- Choose numeration for interfaces
- Configure interfaces
- Provide routing details

#### Choose devices and configure

- Choose device to configure
- Name your device
- Configure security options
- Configure additional settings
- Choose connection options (if to append config with vty and console)
- Enable services
- 

### 2.2 Solving network problems

## Part 3: Manual and Hints