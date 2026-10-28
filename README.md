# Assessment Submission

- **Name:** Aalap Raj
- **Registration number:** 202401100100002
- **Application port:** 82
- **Docker Hub username:** aalapraj
- **Docker Hub repository:** https://hub.docker.com/r/aalapraj/fest-backend
- **AI tool used:** Copilot SDK in VS Code, used to help prepare the container configuration and assessment documentation.
- **Image digest:** `1.0.0` — placeholder only; replace with the digest once the image is pushed and available.

## Trivy Critical/High Findings

| Scan stage | CRITICAL | HIGH | Image size |
|---|---:|---:|---:|
| Before (`fest-backend:0.1`) | 234 | 2243 | 1.613 GB |
| After (`fest-backend:0.2`) | 0 | 0 | 319 MB |

Source: `reports/trivy-before.txt` and `reports/trivy-after.txt`.

**Incomplete steps:** The Docker Hub push and publication of the final image digest are pending.
