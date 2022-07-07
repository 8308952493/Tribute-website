# Tribute-website
Its about basic of Html and css how to build a Tribute Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tribute Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="main">
        <h1 id="title">Netaji Shubhas Chandra Bose</h1>
        <p>The Indian Freedom Fighter.</p>
        
        <div id="img-div">
          <img id="image" alt="Netaji Subhas Chandra Bose" src="kindpng_4414959.png" />
          <figcaption  id="img-caption" >Subhash Chandra Bose was an Indian revolutionary who believed in violent resistance to British rule. He joined the Indian National Army in 1943. One of his most famous declarations was 'Tum mujhe khoon do mai tumhe azadi doonga' (Give me blood, I shall give you freedom).</figcaption>
        </div>
        
        <div id="tribute-info">
          <h3>Here's a time line of Netaji's life:</h3>
          <ul>
            <li><strong>Date of Birth</strong> - January 23, 1897
      </li>
             <li><strong>Place of Birth</strong> - Cuttack, Odisha </li>  
            <li><strong>Parents</strong> - Janakinath Bose (father) and Prabhavati Devi (mother)</li>  
            <li><strong>Spouse</strong> - Emily Schenkl</li>  
            <li><strong>Children</strong> - Anita Bose Pfaff</li>  
            <li><strong>Education</strong> - Ravenshaw Collegiate School ,Cuttack; Presidency College, Calcutta; University of Cambridge, England</li>  
            <li><strong>Associations (Political Party)</strong> - Indian National Congress; Forward Bloc; Indian National Army
            <li><strong>Movements</strong> - Indian Freedom Movement  
            <li><strong>Political Ideology</strong> - Nationalism; Communism; Fascism-inclined</li>  
            <li><strong>Religious Beliefs</strong> - Hinduism
      </li>  
            <li><strong>Subhas Chandra Bose: Family history and early life</strong> - Netaji Subhas Chandra Bose was born on 23 January, 1897 in Cuttack (Orissa)  to Prabhavati Dutt Bose and Janakinath Bose. His father was a successful lawyer in Cuttack and received the title of "Rai Bahadur". He did his schooling from the Protestant European School (presently Stewart High School) in Cuttack, just like his siblings. He did baccalaureate from the Presidency College. He was influenced by the teachings of Swami Vivekananda and Ramakrishna after reading their works at the age of 16. He then was sent by his parents to the University of Cambridge in England to prepare for the Indian Civil Service. In 1920 he passed the civil service examination, but in April 1921, after hearing of the nationalist turmoils in India, he resigned his candidacy and hurried back to India.</li>  
            <li><strong>Subhas Chandra Bose and Indian National Congress</strong> - He joined Non-Cooperation Movement which was started by Mahatama Gandhi who made INC a powerful non-violent organization. During the movement, he was advised by Mahatma Gandhi to work with Chittaranjan Das who became his political guru. After that, he became a youth educator and commandant of the Bengal Congress volunteers. He started the newspaper 'Swaraj'. In 1927, after being released from prison, Bose became general secretary of the Congress party and worked with Jawaharlal Nehru for independence.

                In 1938 he was elected president of the Indian National Congress and formed a national planning committee, which formulated a policy of broad industrialization. However, this did not harmonize with Gandhian economic thought, which clung to the notion of cottage industries and benefiting from the use of the country’s own resources. Bose’s vindication came in 1939 when he defeated a Gandhian rival for reelection. Nonetheless, the “rebel president” felt bound to resign because of the lack of Gandhi’s support.</li>    
          </ul>
          
          <i>"One individual may die for an idea, but that idea will, after his death, incarnate itself in a thousand lives. Freedom is not given – it is taken. Freedom is not given – it is taken. No real change in history has ever been achieved by discussions"</i> <br><br>
          <i>-- Netaji Shubhas Chandra Bose</i>
        </div>
        
        <h5>
          Some Facts about to Netaji to understand the better you can read also  <a id="tribute-link" target="_blank" href="https://www.theceo.in/important-days-in-indian-history/10-interesting-facts-about-subhash-chandra-bose">Facts About Netaji</>.
        </h5>
      </div>
      
    
</body>
</html>
#The css part by side is here
  body {
    font-family: "Lato", sans-serif;
    font-size: 20px;
  }
  
  #main {
    max-width: 1280px;
    max-height: 100%;
    margin: 30px auto;
    padding: 15px;
    background-color: #dddddd;
    border-radius: 5px;
  }
  
  #title {
    text-align: center;
  }
  
  #main > p {
    text-align: center;
  }
  
  #img-div{
    max-width: 800px;
    margin: 0 auto;
    padding: 15px;
    background-color: grey;
  }
  
  #image {
    display: block;
    max-width: 100%;
    padding-bottom: 10px;
  }
  
  #tribute-info {
    max-width: 600px;
    margin: 0 auto;
  }
  
  #tribute-info > h3 {
    text-align: center;
  }
  
  #tribute-info > ul li {
    margin-bottom: 10px;
    line-height: 30px;
  }
  
  h5{
     text-align: center;
  }
