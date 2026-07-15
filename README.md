# Weather Widget Plus (Transparent)

A KDE Plasma weather widget displaying current conditions and forecasts, fetched from [met.no](https://api.met.no/), [Open-Meteo](https://open-meteo.com/), or [OpenWeatherMap](https://openweathermap.org/). This is a transparent-background fork of [Weather Widget Plus](https://github.com/tully-t/weather-widget-plus).

**Original authors:** Tully Turk, Kate Buckley, Martin Kotelnik

![weather.transp](weather-transp.png)
![weather.transp](desktop-1.png)

## Features

- Current temperature, conditions, wind, and precipitation
- Hourly and daily forecast
- Meteogram view (graphical forecast chart)
- Multiple location support
- Supports met.no, Open-Meteo, and OpenWeatherMap providers
- Transparent background — blends into any wallpaper or panel
- Horizontal, vertical, and compact layout modes
- Localised into multiple languages

## Requirements

- KDE Plasma 6.0+
- Internet connection (weather data is fetched live)
- OpenWeatherMap API key (if using the OWM provider)

## Installation

```bash
cd ~/.local/share/plasma/plasmoids/
git clone https://github.com/PlasmaDrifter/weather-transp local.widget.weather-transp
```

Then right-click your desktop or panel → **Add Widgets** → search for **Weather Widget Plus Trans**.

## Configuration

Right-click the widget → **Configure…**

| Option | Description |
|--------|-------------|
| Location | Add one or more locations by name or coordinates |
| Weather provider | met.no (no key needed), Open-Meteo, or OpenWeatherMap |
| Temperature unit | Celsius / Fahrenheit / Kelvin |
| Wind speed unit | m/s / mph / km/h |
| Pressure unit | hPa / inHg / mmHg |
| Layout | Horizontal, Vertical, or Compact |
| Reload interval | How often to fetch fresh weather data (minutes) |

## Credits

Based on [Weather Widget Plus](https://github.com/tully-t/weather-widget-plus) — transparent-background customisation by JMC.

