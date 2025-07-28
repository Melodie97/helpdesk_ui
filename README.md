# Helpdesk UI

A simple chat interface for IT helpdesk support.

## Setup

1. Update the API endpoint in `vercel.json`:
   ```json
   {
     "rewrites": [
       {
         "source": "/api/support",
         "destination": "YOUR_HELPDESK_API_ENDPOINT_HERE"
       }
     ]
   }
   ```

2. Deploy to Vercel or serve locally with `python server.py`

## Usage

Open the chat interface and ask IT support questions. The system categorizes requests and escalates complex issues automatically.