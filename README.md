# EcoScan - Clothing Carbon Footprint Scanner 🌿

* EcoScan is a web application designed to help users understand the environmental impact of their clothing choices. By analyzing images of clothing items, the app calculates their carbon footprint, awards eco-reward points, and showcases redeemable offers for sustainable actions.

-----------------------------------------------------------------------------------

# Features 🚀

A. Frontend:

1. Upload images via file or directly capture using a camera.
2. View detailed analysis:
3. Identified clothing items.
4. Estimated carbon scores.
5. Total eco-reward points via eco-savings quiz.
6. Browse and redeem available offers.

B. Backend:

1. Image Analysis: Recognizes clothing items and estimates their carbon footprint.
2. Carbon Score Calculation: Determines scores based on in-memory assumptions.
3. Offer Management: Displays offers based on eco-reward points.

------------------------------------------------------------------------------------

# Technical Stack 🛠️

1. Frontend: Streamlit
2. Backend: Python
3. Image Recognition: OpenAI’s GPT-4 Vision model (gpt-4o) 
4. In-Memory Storage: Dictionary-based assumptions for carbon scores

-------------------------------------------------------------------------------------

# GETTING STARTED!: 

Prerequisites
1. Python 3.8 or later
2. Streamlit installed (pip install streamlit)
3. OpenAI API key (sign up at OpenAI)
   

--------------------------------------------------------------------------------------

# Installation Guidelines

1. Clone the repository:

         git clone https://github.com/Samraatrichy/Eco-Scan-Challenge
         

2. Install dependencies:

         pip install -r requirements.txt

3. Set up your OpenAI API key:

         OPENAI_API_KEY='your_openai_api_key'
  We have temporarily enabled our own key for use. 
  If it doesn't work, feel free to use your own OpenAI API key.
  

---------------------------------------------------------------------------------------

# Running the Application

* Start the Streamlit server:
    
        streamlit run Ecoscan.py
        (Open localhost:8501 in your browser to view the app)

---------------------------------------------------------------------------------------

# Assumptions for Carbon Scoring 

| S.No | Clothing Item                | Estimated Carbon Footprint (kg CO₂e) |
|------|------------------------------|---------------------------------------|
| 1    | T-shirt (Cotton)            | 5                                     |
| 2    | Jeans (Denim)               | 10                                    |
| 3    | Jacket (Wool or Polyester)  | 15                                    |
| 4    | Shirt (Cotton)              | 4                                     |
| 5    | Sweater (Wool or Acrylic)   | 7                                     |
| 6    | Dress (Cotton or Synthetic) | 8                                     |
| 7    | Shorts (Cotton)             | 4                                     |
| 8    | Hoodie (Cotton)             | 8                                     |
| 9    | Suit (Wool)                 | 20                                    |
| 10   | Coat (Wool or Synthetic)    | 18                                    |
| 11   | Skirt (Cotton)              | 6                                     |
| 12   | Socks (Cotton or Wool)      | 1.5                                   |
| 13   | Underwear (Cotton)          | 1                                     |
| 14   | Tights (Nylon)              | 2                                     |
| 15   | Sportswear (Polyester)      | 7                                     |

* For the full list, refer to the app's data table.

-------------------------------------------------------------------------------------


# Enhancements for Future 🚀
1. Product Improvements
    a. Dynamic Carbon Scores: Integrate real-time data sources for accurate         
       carbon scoring.
    b. Expanded Eco-Insights: Provide users with sustainability tips and comparisons.

2. Technical Scalability
    a. Backend Scaling: Use AWS Lambda or Azure Functions for serverless scaling.
    b. Database Integration: Shift from in-memory storage to a cloud database 
        for persistent data.

---------------------------------------------------------------------------------------

# Deployment on Streamlit Community Cloud
The EcoScan application is deployed and hosted on Streamlit Community Cloud. Users can access the app directly without needing to install any additional dependencies locally.

🚀 Access the Deployed App
Visit the EcoScan app here: https://ecoscanchallenge.streamlit.app/

🌟 Deployment Highlights

Hosted on Streamlit Community Cloud.
No setup required for users—just click the link to access the app.
Automatically updated whenever the GitHub repository is updated (linked with Streamlit Community Cloud).
