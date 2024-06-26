# grenud-lms

PERN stack learning management system.

## General Important Commands

- Installing pnpm using Windows PowerShell

```bash
iwr https://get.pnpm.io/install.ps1 -useb | iex
```

- Creating a new Vite project in the same directory with react-ts template

```bash
pnpm create vite ./ --template react-ts   
```

- Installing dependencies

```bash
pnpm i
```

- Running server

```bash
pnpm run dev
```

- Installing OpenSSH (Windows)

```powershell
Add-WindowsCapability -Online -Name OpenSSH.Client~~~~0.0.1.0
```

- Connecting to the ec2-db-connect1 instance

### Place the EC2-RDS-Connect.pem file in the directory you're in

```bash
ssh -i "EC2-RDS-Connect.pem" ec2-user@ec2-15-206-149-39.ap-south-1.compute.amazonaws.com
```

Run this command, if necessary, to ensure your key is not publicly viewable.

```bash
chmod 400 "EC2-RDS-Connect.pem"
```

- Connecting to the PostgreSQL server via Amazon EC2 Instance

```bash
psql --host=bayava-lms.clykoow2ix8x.ap-south-1.rds.amazonaws.com --port=5432 --username=postgres --password --dbname=bayava_lms
```
