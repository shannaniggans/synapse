


Create the noe for the source URL
[ inet:urlfile=(<URL_HERE>, <SHA256_HERE>) ]

python -m synapse.tools.storm cell:///vertex/storage


```
storm> [ inet:urlfile=(hxxps://cdn-129.anonfiles.com/kbj2L0E7y8/df4b79d3-1667268564/austra
lia.txt, 913e56ef839936e7b0ccdf1b802a16ea5fa68a0b4d97f97c69668e5e8190d8fc) ]
...................................
inet:urlfile=('hxxps://cdn-129.anonfiles.com/kbj2L0E7y8/df4b79d3-1667268564/australia.txt', 'sha256:913e56ef839936e7b0ccdf1b802a16ea5fa68a0b4d97f97c69668e5e8190d8fc')
        :file = sha256:913e56ef839936e7b0ccdf1b802a16ea5fa68a0b4d97f97c69668e5e8190d8fc
        :url = hxxps://cdn-129.anonfiles.com/kbj2L0E7y8/df4b79d3-1667268564/australia.txt
        .created = 2022/11/02 05:35:15.287
complete. 1 nodes in 1148 ms (0/sec).
storm>
```
