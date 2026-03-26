# Project Background
Rice cultivation, or farming, has played a crucial role in the lifestyle of Sri Lankans since 800 B.C. and remains the primary mode of income for 1.8 million farmers in Sri Lanka, covering around 34% of farming land. (Amarasinghe, et al., 2024) (Kularathne, et al., 2024). Even in the twenty-first century. In ancient times, it was known as the “Granary of the East” or “Peradiga Maha Dhanyagaraya” due to the strong connection and commitment people had with paddy. (Loris, 2021)
However, when it comes to profits, farmers lose most of their harvest to pest infections, and this is not a new phenomenon. But the problem is that Sri Lankan farmers struggle to keep up with modern technology, which offers solutions to pest infections. As of 2024, pest outbreaks resulted in 30% to 40% of cultivated crops being lost (Wang, et al., 2024), while rice yields have remained stagnant at 4.3 tons per hectare for the past 40 years. (Agriculture, 2025).  
Although there are a few IT-based solutions on the market that aim to address pest infections, they could also facilitate Sri Lankan farmers who are new to the technology. Currently, most paddy farmers are accustomed to traditional pest-repelling methods, which are not efficient and do not help farmers minimise damage from pest infections.
There is a huge need for a centralised pest monitoring system for the Sri Lankan paddy-farming industry. Which is the reason the “Govi Suraksha” pest monitoring mobile app was designed to provide early warnings, pest identification, and also provide expert support with the help of modern technologies such as NDVI and AI.

# Problem Statement
Sri Lankan farmers, especially paddy farmers, face huge losses when it comes to pest infections due to a lack of guidance and the proper knowledge on how to face the pests effectively that threaten their daily lifestyle to secure their income source.
2024 research shows how much paddy field losses increase in Sri Lanka due to delayed pest detection. Farmers mostly realise crop infections only after huge damage has been done to the crops, leading to delayed treatments. This increases yield loss up to 37% annually, affecting the country’s rice supply and farmer incomes. (Wang, et al., 2024) This is a big problem because it is directly affecting the country’s economy. Currently, there is no proper paddy-field early pest outbreak alert system in Sri Lanka to alert farmers before pest outbreaks according to each district. This causes farmers to use prevention methods after the infection has done much damage to the crops (Savary, et al., 2000), leading to a decrease in annual rice production and farmer income.
Within the Maha season (September 2024 – March 2025), rice harvest dropped to an estimated 2.57 million, which is 5.7% less compared to the previous year (2023). During the Yala season (May – August 2024), around 4778 hectares were lost due to pest infestation and lack of knowledge among the farmers’ communities. (Abeysinghe, 2025)
In addition, even though technological advances have occurred, rice yields in Sri Lanka have barely improved over the last 40 years. A recent study found the country’s rice harvests averaged 4.3 tons per hectare (t/ha) over the last 40 years (Agriculture, 2025) [Refer to Appendices figure 54]. Pests are one of the biggest problems that stop Sri Lanka from getting better rice harvests. Farmers often lose 30% to 40% of their crops because of pest attacks. When rice demand is greater than the supply, the country’s food supply is at risk, leading to importing rice, which affects the country’s economy.
Most of the paddy farmers tend to identify pest infection when the damage is already spread too much. When that happens, farmers tend to misuse pesticides to minimise the crop loss, which is pointless at this stage, and also not healthy. Not having a centralised system that monitors pest outbreaks locally and guides farmers to minimise crop losses can be considered a major disadvantage to the paddy-farming industry in Sri Lanka. The lack of knowledge among farmers about pests also leads them to misuse pesticides, resulting in ineffective treatments and significant expenses.

# Govi-Suraksha Application Design

Govi-Suraksha is a conceptual mobile application designed to support farmers with crop protection and agricultural management. The project focuses on designing a user-friendly interface and planning the system structure for an agricultural assistance platform.
The application concept aims to help farmers access useful information, monitor crop conditions, and make better farming decisions using technology.


# Gap Analysis


| Features | GoviNena | GoviMithuru | Krushi Advisor | Plantix (Germany) | Agrio (Israel) | Farmonaut (India) | RiceClinic (India) | Proposed Solution |
|----------|----------|-------------|----------------|------------------|---------------|------------------|-------------------|------------------|
| **F1: AI-Powered Outbreak Prediction** | No | No | No | Yes | Yes | Yes | No | Yes |
| **F2: Image-Based Pest Identification** | No | No | No | Yes | Yes | No | No | Yes |
| **F3: Community Information Sharing** | Yes | Yes | No | Yes | No | No | No | Yes |
| **F4: Multi-Language Support** | Yes | Yes | No | Yes | Yes | No | No | Yes |
| **F5: Satellite-Based Crop Health Alerts** | No | No | No | No | Yes | Yes | No | Yes |
| **F6: Pest Library** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **F7: Pest Attack Loss Estimator** | No | No | No | Yes | No | No | No | Yes |
| **F8: Weather Forecast** | Yes | No | No | Yes | Yes | No | No | Yes |
| **F9: Farmer Training Programs** | No | No | No | Yes | No | No | No | Yes |
| **F10: Request Field Visits** | No | No | No | No | No | No | No | Yes |
| **F11: Agriculture Office Dashboard** | No | No | No | No | No | No | No | Yes |
| **F12: Monthly Pest Spread Forecast** | No | No | No | No | No | No | No | Yes |
| **F13: Smart Treatment Calendar** | No | No | No | No | No | No | No | Yes |
| **F14: 24/7 Expert Support System** | No | No | No | No | No | No | No | Yes |

## Feature Descriptions

| Feature | Description |
|-------|-------------|
| **F1: AI-Powered Outbreak Prediction** | Uses location, climate data, farmer reports, and global paddy pest trends to predict pest outbreaks and generate early alerts for farmers and government authorities to prepare treatments. |
| **F2: Image-Based Pest Identification** | Farmers can upload images of pests or infected plants. AI, Computer Vision, and Machine Learning analyze the images and identify pests using a centralized database. |
| **F3: Community Information Sharing** | A platform where farmers can share problems, experiences, and solutions. Enables farmer-to-farmer and farmer-to-expert discussions in both public and private forums. |
| **F4: Accessibility Features** | Multi-language support (Sinhala, English, Tamil), offline functionality with sync when online, and optional SMS alerts for important updates. |
| **F5: Satellite-Based Crop Health Monitoring** | Uses satellite imagery and vegetation analysis such as NDVI (Normalized Difference Vegetation Index) to monitor crop health and detect potential pest or crop stress conditions. |
| **F6: Paddy-Field Pest Library** | A centralized agricultural database containing detailed information about paddy pests, symptoms, and recommended treatments. |
| **F7: Pest Attack Loss Estimator** | Estimates potential yield loss by comparing the productivity of pest-infested crops with healthy crops. |
| **F8: Weather Forecast Alerts** | Provides weather forecasts and alerts to help farmers prepare for environmental conditions affecting crops. |
| **F9: Farmer Training Programs** | Government-funded educational video programs designed to help farmers learn pest prevention and effective crop management techniques. |
| **F10: Request Field Visits** | Farmers can request on-site visits from agricultural experts for accurate diagnosis and advice (service charges may apply). |
| **F11: Agricultural Office Dashboard** | A management portal for agricultural authorities to monitor pest outbreaks, manage farmer reports, assign field visits, and identify district-level pest spread zones. |
| **F12: Monthly Pest Spread Forecast** | Provides monthly pest outbreak predictions based on geographic location. Historical forecasts can also be analyzed to improve future predictions. |
| **F13: Smart Treatment Calendar** | Farmers can enter the seeding date, and the system automatically generates a schedule for farming activities, treatments, and best pest control measures until harvest. |
| **F14: Expert Support System** | Farmers can communicate with agricultural experts and government officers via chat or video call for real-time assistance and advice. |


## Project Features

- UI/UX design for a farmer support application
- Concept for agricultural information management

## Purpose

The goal of this project is to explore how digital tools and mobile applications can assist farmers by providing accessible agricultural information and improving farm management.

## Technologies / Tools Used

- Figma (UI design)


## Author

**Anupama Omiru**  
Computer Science Undergraduate

Figma Link:
https://www.figma.com/design/rdMnDP458B2geI5dPgWEzl/Govi_Suraksha_Prototype?m=auto&t=xByeeU6dGwObdI8m-1

Gmail:
omiru.dasanayake@gmail.com
