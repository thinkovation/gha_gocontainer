# Use a minimal base image
FROM scratch

# Copy the built Go executable into the container image
COPY app /app

# Expose port 8080 to the outside world
EXPOSE 8080

# Set environment variable for HTTP_PORT (default to 8080)
ENV HTTP_PORT=8080

# Set the entry point of the container
ENTRYPOINT ["/app"]
