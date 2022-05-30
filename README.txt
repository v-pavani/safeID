REQUIRED ENVIRONMENT VARIABLES

The following environment variables must be set for database connectivity:

All envs:
NTID={core PDB username, must match all environments}
 
Stage:
StagePDBpw={core PDB password for Stage DB server}
StageIsecDbPw={Isec DB password for Stage DB server}
StageMyUhcPdbPw={MyUhc PDB password for Stage DB server}
StageOptumRxPdbPw={OptumRx PDB password for Stage DB server}


Test:
TestPDBpw={core PDB password for Test DB server}
TestIsecDbPw={Isec DB password for Test DB server}
TestMyUhcPdbPw={MyUhc PDB password for Test DB server}

OPTIONAL ENVIRONMENT VARIABLES
If the following are not set, the test framework will use default values.

SAUCE_USERNAME={your sauceLabs username}
SAUCE_ACCESS_KEY={your saceLabs access Key}
	Note: Access key is obtained by logging into saucelabs, going to your account page, and copying 
	from there.