Project Title
--------------
Cloud Stones Platform

# Pre-Requisites
The below commands to set environment variables in Windows machine

vi setenv.cmd
set AZURE_SUBSCRIPTION_ID="aa11bb33-cc77-dd88-ee99-0918273645aa"

set AZURE_TENANT_ID=00112233-7777-8888-9999-aabbccddeeff

set AZURE_CLIENT_ID=12345678-1111-2222-3333-1234567890ab

set AZURE_CLIENT_SECRET=oUBB11zz~JJJJ_~yyyyyyVVumumumumb_b


az login

export MSYS_NO_PATHCONV=1
az ad sp create-for-rbac --name <myserviceprincipal> --role Contributor

https://docs.microsoft.com/en-us/azure/developer/python/configure-local-development-environment?tabs=cmd



Execution Flow
----------------
$git clone https://github.com/csp2022/CSP.git

$cd CSP/aws

$python3 vpc.py <accesskeyid> <secretaccesskey>
