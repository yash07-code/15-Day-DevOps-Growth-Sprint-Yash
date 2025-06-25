 Day 5: Kubernetes Secrets & ConfigMaps Mastered!
🗓️ hashtag#Day5 of my 30-Day DevOps Sprint
Today, I dove deep into two core building blocks of Kubernetes app configuration:
🔐 Kubernetes Secrets
 I learned how to securely store sensitive data like API keys, passwords, and tokens in base64-encoded form. From creating secrets via kubectl to mounting them as environment variables or volumes — I now understand how to keep credentials safe and separate from code.

⚙️ Kubernetes ConfigMaps
 ConfigMaps taught me the DevOps way of externalizing environment-specific configuration (like config files, DB URLs, and feature flags) so the same app code works across environments (dev/stage/prod) with ease.

✅ Hands-on:
Created and applied both Secrets and ConfigMaps YAMLs.
Injected them into Pods via env & volume.
Used kubectl describe, get, and logs to validate config loading.
Next time you deploy a microservice on Kubernetes, don’t hardcode — ConfigMap it or Secret it! 
