FROM jupyter/scipy-notebook

# Install any additional packages you need, e.g. pandas
RUN conda install --quiet --yes pandas

# Copy the notebook to the container
COPY process_email.ipynb /home/jovyan/work/

# Set the working directory
WORKDIR /home/jovyan/work/