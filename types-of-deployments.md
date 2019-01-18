| Method | Imapact of Failed Deployment | Deploy Time | Zero Downtime | No DNS Change | Rollback Process | Code Deployed to |
| --- | --- | --- | --- | --- | --- | --- |
| Deploy in Place | Downtime |   | X | OK | Redeploy | Existing instances |
| Rolling | Single batch out of service, any succesful batches prior to failure running new application version | @@ | OK | OK | Redeploy | Existing instaces |
| Rolling with additional batch | Minimal of first batch fails, otherwise similar to rolling | @@@ | 
