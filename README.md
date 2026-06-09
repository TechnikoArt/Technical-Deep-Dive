##[debug]Starting: Set up job
Current runner version: '2.334.0'
Runner Image Provisioner
Operating System
Runner Image
GITHUB_TOKEN Permissions
Secret source: Actions
##[debug]Primary repository: pumpcommandcenter/Technical-Deep-Dive
Prepare workflow directory
##[debug]Creating pipeline directory: '/home/runner/work/Technical-Deep-Dive'
##[debug]Creating workspace directory: '/home/runner/work/Technical-Deep-Dive/Technical-Deep-Dive'
##[debug]Update context data
##[debug]Evaluating job-level environment variables
##[debug]Evaluating job container
##[debug]Evaluating job service containers
##[debug]Evaluating job defaults
Prepare all required actions
Getting action download info
Error: Unable to resolve action `apisec-inc/ethicalcheck-action`, not found
##[debug]GitHub.DistributedTask.WebApi.UnresolvableActionDownloadInfoException: Unable to resolve action `apisec-inc/ethicalcheck-action`, not found
##[debug]   at GitHub.Services.Launch.Client.LaunchHttpClient.GetResolveActionsDownloadInfoAsyncV2(Guid planId, Guid jobId, ActionReferenceList actionReferenceList, CancellationToken cancellationToken)
##[debug]   at GitHub.Runner.Worker.ActionManager.GetDownloadInfoAsync(IExecutionContext executionContext, List`1 actions)
##[debug]   at GitHub.Runner.Worker.ActionManager.GetDownloadInfoAsync(IExecutionContext executionContext, List`1 actions)
##[debug]   at GitHub.Runner.Worker.ActionManager.PrepareActionsRecursiveLegacyAsync(IExecutionContext executionContext, PrepareActionsState state, IEnumerable`1 actions, Int32 depth, Guid parentStepId)
##[debug]   at GitHub.Runner.Worker.ActionManager.PrepareActionsAsync(IExecutionContext executionContext, IEnumerable`1 steps, Guid rootStepId)
##[debug]   at GitHub.Runner.Worker.JobExtension.InitializeJob(IExecutionContext jobContext, AgentJobRequestMessage message)
##[debug]Finishing: Set up job
