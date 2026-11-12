1. Service models
Streamlit Community Cloud is PaaS: you bring the code, it provides the runtime, servers and URL. GitHub is SaaS: a finished application you use in
the browser

2. Jobs you 2did not do
Any two: buy or rent a server, install the OS, install Python, configure a web server, open firewall ports, get a domain/URL, patch software

3. Why requirements.txt?
The platform builds a fresh environment for your app. requirements.txt tells it which packages (streamlit, pandas, matplotlib) to install; without it
the app fails with ModuleNotFoundError.
