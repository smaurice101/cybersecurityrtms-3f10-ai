Latest Logs From Latest Build
==============================

Generated On: 2025-04-11 22:19:47 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/smaurice101/raspberrypitss/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2025-04-11_22:13:17] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2025-04-11_22:13:24] STEP 2: Create topics started

  [INFO 2025-04-11_22:16:43] STEP 2: Completed

  [INFO 2025-04-11_22:16:51] STEP 3: producing data started

  [INFO 2025-04-11_22:16:55] STEP 4: Preprocessing started

  [INFO 2025-04-11_22:16:57] STEP 3: reading local file..successfully

  [INFO 2025-04-11_22:16:59] STEP 4a: Preprocessing started

  [INFO 2025-04-11_22:17:03] STEP 4: Preprocessing started

  [INFO 2025-04-11_22:17:07] STEP 4a: Preprocessing started

  [INFO 2025-04-11_22:17:08] STEP 7: Visualization started

  [INFO 2025-04-11_22:17:17] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 49689

  [INFO 2025-04-11_22:17:34] STEP 4c: Preprocessing 3 started

  [INFO 2025-04-11_22:17:35] STEP 9: Qdrant container.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant, v=0

  [INFO 2025-04-11_22:17:35] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2025-04-11_22:17:40] STEP 9: Starting privateGPT

  [INFO 2025-04-11_22:17:54] STEP 8: Starting docker push for: maadsdocker/cybersecurityrtms-3f10-ai-amd64

  [INFO 2025-04-11_22:18:09] STEP 9: PrivateGPT container.  Here is the run command: docker run -d -p 8001:8001 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z --env PORT=8001 --env TSS=1 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env vectorsearchtype="Manhattan" --env contextwindowsize=4096 --env vectordimension=768 --env mainmodel="mistralai/Mistral-7B-Instruct-v0.2" --env mainembedding="BAAI/bge-small-en-v1.5" maadsdocker/tml-privategpt-with-gpu-nvidia-amd64-v2, v=0

  [INFO 2025-04-11_22:18:09] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z --env PORT=8001 --env TSS=1 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env vectorsearchtype="Manhattan" --env contextwindowsize=4096 --env vectordimension=768 --env mainmodel="mistralai/Mistral-7B-Instruct-v0.2" --env mainembedding="BAAI/bge-small-en-v1.5" maadsdocker/tml-privategpt-with-gpu-nvidia-amd64-v2

  [INFO 2025-04-11_22:19:22] STEP 8: Docker Container created and optimized.  Will push it now.  Here is the commit command: docker commit dc4e780d1059 maadsdocker/cybersecurityrtms-3f10-ai-amd64 - message=0

  [INFO 2025-04-11_22:19:46] STEP 10: Started to build the documentation

  [INFO 2025-04-11_22:19:48] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


