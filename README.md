# MitsuRunner - puu's setup

This is my personal setup of the MitsuRunner software that is originally located in https://github.com/VeliML/MitsuRunner.

I have a first generation MSZ-LN25 heat pump that has serious "hullunkierto" (frequent defrosting) problem. Before installing Mitsurunner hack, it defrosted practically whole winter every 40-50 minutes. Now with Mitsurunner heat production in cold winter days is much better thanks to reasonable defrost frequency.

## Changes to the original SW and HW:
- Two additional Dallas sensors in heat exchanger pipes (used for research and as spare parts)
- Current clamp sensor monitoring input power of the heat pump
- DHT11 sensor (commented out in the code, not used currenlty but left for reference)
- Variable temperature delta threshold to start defrosting
