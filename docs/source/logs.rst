Latest Logs From Latest Build
==============================

Generated On: 2025-03-21 18:21:03 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/smaurice101/raspberrypitss/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2025-03-21_18:13:15] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2025-03-21_18:13:18] STEP 2: Create topics started

  [INFO 2025-03-21_18:18:23] STEP 2: Completed

  [INFO 2025-03-21_18:18:28] STEP 3: producing data started

  [INFO 2025-03-21_18:18:31] STEP 4: Preprocessing started

  [INFO 2025-03-21_18:18:33] STEP 7: Visualization started

  [INFO 2025-03-21_18:18:43] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 49689

  [INFO 2025-03-21_18:18:49] STEP 4: Preprocessing started

  [INFO 2025-03-21_18:18:53] STEP 3: reading local file..successfully

  [INFO 2025-03-21_18:18:59] STEP 9: Qdrant container.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant, v=0

  [INFO 2025-03-21_18:18:59] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2025-03-21_18:19:04] STEP 9: Starting privateGPT

  [WARN 2025-03-21_18:19:05] STEP 9: PrivateGPT container not found. It may need to be pulled if it does not start: docker pull maadsdocker/tml-privategpt-with-gpu-nvidia-amd64-v2

  [INFO 2025-03-21_18:19:35] STEP 8: Starting docker push for: maadsdocker/cybersecurityrtms-3f10-ai-amd64

  [INFO 2025-03-21_18:20:54] STEP 8: Docker Container created and optimized.  Will push it now.  Here is the commit command: docker commit 4b2e99c37eb6 maadsdocker/cybersecurityrtms-3f10-ai-amd64 - message=0

  [INFO 2025-03-21_18:21:03] STEP 10: Started to build the documentation

  [INFO 2025-03-21_18:21:04] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


