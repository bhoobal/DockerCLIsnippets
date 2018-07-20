# DockerCLIsnippets

to switch between windows and linux container mode

$Env:ProgramFiles\Docker\Docker\DockerCli.exe -SwitchDaemon

docker version


docker info
# System wide info about docker

PS C:\WINDOWS\system32> docker info
		Containers: 12
		 Running: 0
		 Paused: 0
		 Stopped: 12
		Images: 13
		Server Version: 18.03.1-ce
		Storage Driver: windowsfilter
		 Windows:
		Logging Driver: json-file
		Plugins:
		 Volume: local
		 Network: ics l2bridge l2tunnel nat null overlay transparent
		 Log: awslogs etwlogs fluentd gelf json-file logentries splunk syslog
		Swarm: inactive
		Default Isolation: hyperv
		Kernel Version: 10.0 16299 (16299.431.amd64fre.rs3_release_svc_escrow.180502-1908)
		Operating System: Windows 10 Pro
		OSType: windows
		Architecture: x86_64
		CPUs: 4
		Total Memory: 15.89GiB
		Name: BPALANI-IN-LE02
		ID: OR5W:2DSO:KU7R:QAZR:3FWP:U7FE:JVW6:SFZ7:2AXV:HDHL:L2OA:6PRF
		Docker Root Dir: C:\ProgramData\Docker
		Debug Mode (client): false
		Debug Mode (server): true
		 File Descriptors: -1
		 Goroutines: 43
		 System Time: 2018-07-20T10:50:32.2324958+05:30
		 EventsListeners: 1
		Registry: https://index.docker.io/v1/
		Labels:
		Experimental: false
		Insecure Registries:
		 127.0.0.0/8
		Live Restore Enabled: false

docker pull microsoft/windowsservercore:ltsc2016
