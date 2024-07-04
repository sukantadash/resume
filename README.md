  421  cd Desktop/MyFiles/Sukanta/instruct-lab-demo
  423  python3 -m venv venv
  425  source venv/bin/activate
  426  pip3 install instructlab
  429  ilab --version
  430  ilab init
  432  vi config.yaml
  433  ilab download
  434  vi config.yaml
  435  ilab serve --model-family merlinite --model-path models/merlinite-7b-lab-Q4_K_M.gguf



  417  cd Desktop/MyFiles/Sukanta/instruct-lab-demo
  419  source venv/bin/activate
  420  ilab --version
  421  ilab chat --model-family merlinite -m models/merlinite-7b-lab-Q4_K_M.gguf# resume
