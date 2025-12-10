# python-practice
Step-by-Step Guide to Install Jupyter Notebook Using Anaconda Prompt

1. LAUNCH ANACONDA PROMPT
   • Open Start Menu
   • Search for "Anaconda Prompt"
   • Right-click and select "Run as administrator" (recommended)

2. CREATE A DEDICATED ENVIRONMENT (Optional but Recommended)
   • Create new environment:
        conda create -n python_practice python=3.9
   • Activate the environment:
        conda activate python_practice

3. INSTALL JUPYTER NOTEBOOK
   • Install Jupyter:
        conda install jupyter notebook
   • Press 'y' when prompted to confirm installation

4. LAUNCH JUPYTER NOTEBOOK
   • Start Jupyter:
        jupyter notebook
   • This automatically opens the interface in your default web browser

5. CREATE A NEW PYTHON NOTEBOOK
   • In the browser interface, click "New" button
   • Select "Python 3" (or your environment kernel if created)

6. SHUTDOWN AND DEACTIVATE
   • Save all notebook files
   • Close the browser tab
   • In Anaconda Prompt, press Ctrl+C twice
   • Deactivate environment:
        conda deactivate

Useful Commands for Reference:
• Check installed packages: conda list
• List all environments: conda env list
• Delete an environment: conda remove -n python_practice --all
• Update conda: conda update conda
• Update all packages: conda update --all

Troubleshooting Tips:
• If Jupyter doesn't launch, try: jupyter notebook --no-browser
• To use specific environment in Jupyter: conda install ipykernel
• Clear terminal: cls (Windows) or clear (Mac/Linux)
