
!!!GUTHUB WEBHOOK!!!

* The endpoint is at:

```bash
POST http://127.0.0.1:5000/webhook/receiver
```

For PUSH action:

```bash
Format: {author} pushed to {to_branch} on {timestamp}
```
For PULL_REQUEST action:

```bash
Format: {author} merged branch {from_branch} to {to_branch} on {timestamp}{author} submitted a pull request from {from_branch} to {to_branch} on
{timestamp}
```

For MERGE action:
```bash
Format: {author} merged branch {from_branch} to {to_branch} on {timestamp}
```




