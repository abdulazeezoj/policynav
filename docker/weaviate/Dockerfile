# Use an official Weaviate runtime as a parent image
FROM semitechnologies/weaviate:1.23.0

# Make port 8080 & 50051 available to the world outside this container
EXPOSE 8080
EXPOSE 50051

# Run weaviate when the container launches
CMD ["--host", "0.0.0.0", "--port", "8080", "--scheme", "http"]
