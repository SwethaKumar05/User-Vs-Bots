# User-Vs-Bots
This dataset contains profile data collected from VK.com (VKontakte), Russia's largest social network, for distinguishing between genuine users and automated bots. The data includes both numerical and categorical features extracted from user profiles.

Data Collection:
Collected from public VK.com profiles.
Includes both verified human users and verified bot accounts.
Represents realistic social network conditions with incomplete profiles.

Feature Types:
Numerical Features (NaN values preserved):
Activity metrics (average posts per week, hashtag usage, etc.)
Friend/follower counts.
Categorical Features (missing values marked as 'unknown'):
Profile attributes (has_photo, has_mobile, etc.)
Privacy settings (is_closed_profile, etc)
Binary flags (can_post, can_message, etc)

Data Processing:
Missing values handled differently by feature type:
Categorical: Filled with 'unknown' string
Numerical: Preserved as NaN
Boolean values converted to binary (0/1) where applicable

Potential Use Cases:
Binary classification (user vs bot detection)
Social media behavior analysis
Anomaly detection in social networks
Feature engineering exercises
Dataset Size:
5874 rows × 60 features (balanced 50/50))
