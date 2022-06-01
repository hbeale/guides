# Example lab notebook

Server/Computer: courtyard
Login ID: hcbeale

Time: 2022.06.01_12.35.13



command

```
your_username=hcbeale
mkdir /public/home/${your_username}/public_html
chmod 755 /public/home/${your_username}/public_html
```

commands in terminal with any stdout or stderr

```
11:47 [courtyard:hcbeale]$ your_username=hcbeale
11:52 [courtyard:hcbeale]$ mkdir /public/home/${your_username}/public_html
11:52 [courtyard:hcbeale]$ chmod 755 /public/home/${your_username}/public_html

```

command

```
id_gene_mut=G27349_HRAS_G61
cat ${id_gene_mut}.ann.vcf  | grep -A1 '#CHROM' | cut -f9,10 | tail -1 | tr "\t" "\n" | rowsToCols stdin stdout -fs=:
```

commands in terminal with any stdout or stderr

```
15:27 [courtyard:~]$ cat ${id_gene_mut}.ann.vcf  | grep -A1 '#CHROM' | cut -f9,10 | tail -1 | tr "\t" "\n" | rowsToCols stdin stdout -fs=:
GT      0/1
DP      885
AD      506,378
RO      506
QR      17018
AO      378
QA      12695
GL      -876.455,0,-1263.45
15:30 [courtyard:~]$ 
 
```
