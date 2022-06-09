# Custom Nuclei Templates

## How to Run

- Download the files or repository locally
- Run with Nuclei 

## Sample Runs

Install the nuclei scanner https://github.com/projectdiscovery/nuclei 

```sh
git clone https://github.com/psc4re/nuclei-templates.git
cd nuclei-templates
nuclei -t ./* -u https://targets
```
CVE-2002-1388:

```sh
nuclei -t ./cve-2022-1388.yaml -u https://targetf5dotcom
