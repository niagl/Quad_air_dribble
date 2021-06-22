# Quadcopter Air Dribble

### Installation


Recommended OS [Ubuntu 16](http://releases.ubuntu.com/16.04/) to run the code


##### Installing Dependencies


  - Install latest version of [V-Rep Pro Edu](http://www.coppeliarobotics.com/downloads.html)
  - [Python 2.7](https://www.python.org/downloads/release/python-2715/) is required
  - Install latest version of tensorflow using [pip install tensorflow](https://www.tensorflow.org/install)


##### To run simulator


Navigate to where simulator is downloaded and use path of provided environment file


./vrep.sh quad_env.ttt


To run in headless mode
./vrep.sh -h quad_env.ttt


##### To run code


Download provided code and navigate to the downloaded folder


$ python main.py [algorithm] [action] [number of episodes] [steps per episode]


###### Various modes code can be run in


| options | values |
| ------ | ------ |
| algorithm | pg or vpg or ppo |
| action | eval or train |
| number of episodes | default = 200 |
| steps per episode | default = 50 |

