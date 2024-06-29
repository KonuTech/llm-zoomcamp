# Start from the base ollama image
FROM ollama/ollama

# Set the working directory inside the container
WORKDIR /root/.ollama

# Copy the local weights directory into the container
COPY ollama_files /root/.ollama

# Run the container command (if needed)
CMD ["ollama"]
