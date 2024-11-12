Latest Logs From Latest Build
==============================

Generated On: 2024-11-12 18:33:57 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/osayeni/newsamuelprj2/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-12_18:18:17] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-12_18:18:25] STEP 2: Create topics started

  [INFO 2024-11-12_18:19:13] STEP 2: Completed

  [INFO 2024-11-12_18:19:36] STEP 3: producing data started

  [INFO 2024-11-12_18:19:50] STEP 4: Preprocessing started

  [INFO 2024-11-12_18:19:52] MQTT connection established...

  [INFO 2024-11-12_18:19:58] STEP 4: Preprocessing started

  [INFO 2024-11-12_18:20:02] STEP 7: Visualization started

  [INFO 2024-11-12_18:20:13] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-12_18:21:28] STEP 9: Starting privateGPT

  [INFO 2024-11-12_18:21:54] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-11-12_18:21:58] STEP 8: Starting docker push for: osayeni/latestprojectnewfinal-00f8-amd64

  [INFO 2024-11-12_18:28:11] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 2bd75a9fc403 osayeni/latestprojectnewfinal-00f8-amd64 - message=0

  [INFO 2024-11-12_18:33:20] STEP 8: Successfully ran Docker push: docker push osayeni/latestprojectnewfinal-00f8-amd64 - message=0

  [INFO 2024-11-12_18:33:56] STEP 10: Started to build the documentation

  [INFO 2024-11-12_18:34:00] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


