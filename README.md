# UdaPeople

This project should help you to master CI/CD concepts. The detailed description can be found in [Introduction](instructions/Instructions.md).

## Project Submission Items
### Presentation
The following [slides](./presentation.pdf) explain the key benefits of CI/CD for Cloud-based software products.

### Urls
- Public Url to GitHub repository [URL01]
  - https://github.com/OlgaLyudchik/udacity-cloud-devops-project-udapeople

- Public URL for the S3 Bucket (the green candidate frontend) [URL02]
  - http://udapeople-f92c214.s3-website-us-west-2.amazonaws.com/index.html

- Public URL for the CloudFront distribution (the blue production frontend) [URL03]
  - d1lhzqzgkfq7e8.cloudfront.net

- Public URLs to deployed application backend in EC2 [URL04]
  - ec2-34-216-61-0.us-west-2.compute.amazonaws.com
  - http://ec2-34-216-61-0.us-west-2.compute.amazonaws.com:9100/metrics

- Public URL to the Prometheus server [URL05]
  - http://ec2-54-202-177-103.us-west-2.compute.amazonaws.com:9090

### Screenshots
1. Backend build failed: ![SCREENSHOT01](screenshots/[S01]_backend_build_failed.png)
2. Backend test failed: ![SCREENSHOT02](screenshots/[S02]_backend_test_failed.png)
3. Backend scan failed: ![SCREENSHOT03](screenshots/[S03]_scan_backend_failed.png)
4. Slack CircleCI integration: ![SCREENSHOT04](screenshots/[S04]_slack_alert_integration.png)
5. Deploy backend infrastructure failed: ![SCREENSHOT05](screenshots/[S05]_deploy_backend_failed.png)
6. Frontend smoke test failed: ![SCREENSHOT06](screenshots/[S06]_frontend_smoke_test_failed.png)
7. Rollback after failed smoke test succeeded: ![SCREENSHOT07](screenshots/[S07]_rollback_after_failed_smoke_test.png)
8. Promotion of infrastructure succeeded: ![SCREENSHOT08](screenshots/[S08]_update_cloudfront_succeeded.png)
9. Cleanup old stack succeeded: ![SCREENSHOT09](screenshots/[S09]_cleaup_old_stack_succeeded.png)
10. Skip deployment for non-`main` branch: ![SCREENSHOT10](screenshots/[S10]_skip_deployment_for_non-main_branch.png)
11. Graphs for backend EC2 server that monitor disk I/O, available memory, available disk space, and CPU usage.
    1. Disk I/O ![SCREENSHOT11-1](screenshots/[S11-1]_monitoring_disk_io.png)
    2. Available memory ![SCREENSHOT11-2](screenshots/[S11-2]_monitoring_available_memory.png)
    3. CPU usage ![SCREENSHOT11-3](screenshots/[S11-3]_monitoring_cpu_usage.png)
12. Slack Prometheus integration: ![SCREENSHOT12](screenshots/[S12]_slack_prometheus_integration.png)
