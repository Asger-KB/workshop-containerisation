# TODO: Pick a pinned Python base image (e.g. python:3.12-slim)
FROM ...

WORKDIR /app

# TODO: Copy requirements.txt and install the pinned dependencies with pip
#       Hint: --no-cache-dir keeps the image smaller

# TODO: Copy the notebook(s) and data into /app

COPY data/sales.csv /data/sales.csv

# TODO: Expose the Jupyter port (default 8888)

# TODO: Set the entrypoint to start Jupyter Lab so it's reachable from your host browser.
#       Hints:
#         - bind to 0.0.0.0 (containers can't see localhost from the host)
#         - disable the browser auto-open
#         - set a fixed token so you don't have to dig it out of the container logs
ENTRYPOINT ["jupyter", "lab", "--ip=0.0.0.0", "--no-browser", "--allow-root", "--IdentityProvider.token=workshop"]
