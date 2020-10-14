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
- Generate step-by-step manual for device configuration
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
- Display SbS config

### 2.2 Solving network problems

- Checking ip adressing on your network
- Checking interfaces statuses
- Checking gateways
- Checking line interfaces statuses

## Part 3: Manual and Hints

- Provide overview of selected configuration
- Generate manual for configuration
- Append manual with hints and good practises


# File structure

## Sugested hierarchy

- main.cpp
  - switch.cpp -> // Configure preinitialized switch
  - router.cpp -> // Configure preinitialized router
  - pc.cpp -> // Configure pc to connect with static adressing
  - connection.cpp -> // Sets up connection details
  - adressing.cpp -> // Creates network as object and collectivises devices included, gateways and external facing ports 
  - routing.cpp -> // Creates routers between networks
  - initial.cpp -> // Gathers basic infor about planed configuration