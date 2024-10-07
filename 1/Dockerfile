# Use an official Jupyter image
FROM jupyter/scipy-notebook:latest

# Set the working directory to /home/jovyan (default user in jupyter/scipy-notebook)
WORKDIR /home/jovyan

# Optional: Install additional packages
RUN pip install numpy pandas matplotlib statsmodels seaborn

# Expose the default Jupyter port
EXPOSE 8888

# Set a default password (for security, it’s recommended to configure password protection)
ENV JUPYTER_TOKEN='your_token'

# Command to start Jupyter
CMD ["start-notebook.sh", "--ip=0.0.0.0", "--no-browser", "--allow-root"]
