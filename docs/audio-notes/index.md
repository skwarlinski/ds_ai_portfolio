---
hide:
    - toc
---
<div style="display: flex; align-items: center; gap: 20px; margin-bottom: 30px;">
    <img src="audio_notes.png" 
         width="80" 
         style="background-color: transparent; 
                border-radius: 16px; 
                padding: 12px;
                filter: drop-shadow(0 4px 8px rgba(255, 75, 75, 0.2));
                flex-shrink: 0;">
    <div>
        <h1 style="margin: 0; font-size: 2.5em; color: #ff4b4b;">Audio Notes</h1>
        <p style="margin: 5px 0 0 0; color: #666; font-size: 1.1em;">Aplikacja w Streamlit do nagrywania notatek głosowych z automatyczną transkrypcją i inteligentnym wyszukiwaniem semantycznym.</p>
    </div>
</div>

<div style="text-align: center; margin: 30px 0;">
    <a href="https://github.com/skwarlinski/audio-notes" 
       target="_blank" 
       rel="noopener noreferrer"
       style="display: inline-block; 
              background-color: #ff4b4b; 
              color: white; 
              padding: 15px 30px; 
              text-decoration: none; 
              border-radius: 8px; 
              font-size: 18px; 
              font-weight: bold;
              box-shadow: 0 4px 8px rgba(0,0,0,0.2);
              transition: all 0.3s ease;">
        🔗 Przejdź do repozytorium
    </a>
</div>

### **Audio Notes** to proste narzędzie w Streamlit, które umożliwia nagrywanie głosu, automatyczną transkrypcję przy użyciu OpenAI Whisper oraz zapisywanie i przeszukiwanie notatek w wektorowej bazie Qdrant.

<div class="grid" markdown>
    Wykorzystane technologie i biblioteki

    - Python
    - Streamlit
    - OpenAI API:
        * Whisper-1
        * Text-embedding-3-large
    - Qdrant
    - Pydantic
    - Github
    - Conda

</div>