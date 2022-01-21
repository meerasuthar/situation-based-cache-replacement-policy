# Situation Based Cache Replacement Policy

Install ChampSim simulator using the following command:
```
git clone https://github.com/ChampSim/ChampSim.git
```

Install traces by executing the following command:
```
cd scripts
./download_dpc3_traces.sh
```

Copy the file sbrp.llc_repl into the replacement folder inside the ChampSim folder.
Then execute the following command (From ChampSim folder):
```
./build_champsim.sh bimodal no no no no sbrp 1 
./run_champsim.sh bimodal-no-no-no-no-sbrp-1core 1 10 <trace>
```

<trace> represents a file from dpc3_traces folder. Select one file at a time to execute.
This will generate a file in a results_10M folder. In all the result files in this folder, the lines with LLC* are of interest to us.

In the report, we have included the results we got after running the traces for 7 of 20 traces of dpc3_traces folder.
  
  
# Presented by
ms12418@nyu.edu – Meera Suthar
hp2178@nyu.edu - Harsh Patel

