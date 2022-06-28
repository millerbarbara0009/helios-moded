ssh snx@20.210.126.14

#frist command
```
wget https://github.com/ghostmirrorlab/scripts/raw/main/docker.sh
```

```
bash docker.sh
```

```
pip3 install google-api-python-client google-auth-httplib2 google-auth-oauthlib
python3 generate_drive_token.py
```

#for download sa account
```
python3 gen_sa_accounts.py --download-keys apt-reference-351916
```


```
sudo docker build . -t sa
```

```
sudo docker run sa
```

