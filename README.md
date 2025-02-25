# GCP_CR_Signing_Key_Backend
GCP Cloud Run internal-only API for requesting a signing key from a different (not CR execution SA) configured service accounts.  Targeting splitting the permissions from the Cloud Run SA from the GCS interaction permissions.

This can also allow for correlating the GCS logs with the signing SA, to the specific HTTPS request to Cloud Run for a signed URL.