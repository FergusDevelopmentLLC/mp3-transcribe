```
$ pip3 install pydub install --upgrade speechrecognition
$ python3 transcribe.py
```
You will need a file called api-key.json in root dir.
It should look like this, with your google info.

```
{
  "type": "service_account",
  "project_id": "",
  "private_key_id": "8abab46b15a7398d323b62c8c25e541822c6207e",
  "private_key": "-----BEGIN PRIVATE KEY-----\\n-----END PRIVATE KEY-----\n",
  "client_email": "mp3-to-transcript@mp3-to-transcript.iam.gserviceaccount.com",
  "client_id": "",
  "auth_uri": "https://accounts.google.com/o/oauth2/auth",
  "token_uri": "https://oauth2.googleapis.com/token",
  "auth_provider_x509_cert_url": "https://www.googleapis.com/oauth2/v1/certs",
  "client_x509_cert_url": "https://www.googleapis.com/robot/v1/metadata/x509/mp3-to-transcript%40mp3-to-transcript.iam.gserviceaccount.com"
}
```
More info on setting up the speech recognition api here: https://pypi.org/project/SpeechRecognition/

Troubleshooting: https://github.com/Uberi/speech_recognition/issues/294