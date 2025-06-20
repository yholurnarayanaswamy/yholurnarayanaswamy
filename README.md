```python
class ETLPipeline:
    def __init__(self):
        self.name = "yashwanth_life_cycle"
        self.extract = {
            "source": "Illinois Institute of Technology",
            "Degree": "Information Technology and Management",
            "data_feeds": ["2024–2025: Graduate Assistant","2020–2023: Mcube", "2019–2020: NAL"]
        }
         self.transform = {
            "leisure_loops": [
                "Debugging at odd hours",
                "Visualizing data (and sometimes dreams)"
            ],
        }
        self.load = {
            "outputs": [
                "Actionable dashboards",
                "Reliable pipelines",
                "Business wins",
                "Happier teams"
            ],
            "system_status": "99.9% uptime, only crashed twice (blame the coffee)"
        }

    def log(self):
        print(">> Alert: New challenges detected! Initiating ETL for the next adventure...")

# Instantiate and view the ETL pipeline
etl = ETLPipeline()
print(etl.__dict__)
etl.log()

