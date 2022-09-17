java -jar ApplitoolsSimpleTestRunner.jar batches/job.xml "-var[App_Base_URL,<BASE_URL>]" "-var[App_Name,<APP_NAME>]" "-var[Batch_Name,<Batch_NAME>]" "-var[Targetted_Env,chromeLocally_600X600]"

Ultrafast Grid Execution ::
java -jar ApplitoolsSimpleTestRunner.jar batches/job.xml "-var[App_Base_URL,<BASE_URL>]" "-var[App_Name,<APP_NAME>]" "-var[Batch_Name,<Batch_NAME>]" "-var[Targetted_Env,ultra_fast_headless]"


java -jar ApplitoolsSimpleTestRunner.jar batches/job.xml  "-var[JiraUrl,https://applitools.atlassian.net/]" "-var[UserName,Prasant.sutaria@applitools.com]" "-var[Password,Honeywell25]" "-var[targeted_browsers,chromeLocally_600X600]" -narrate
