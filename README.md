# NuPack markup calculation

NuPack is a famouse packaging service company. When the client asks to repackage existing products, it needs to quickly provide  estimate of the cost. This application is able to calculate markup price. Different markups will be calculated by the conditions.
1. Basic markup : there is a flat markup on all jobs of 5%.
2. It will be added 1.2% by each person that needs to work on the job.
3. Additional markup 
 * Pharmaceuticals : 7.5% markup
 * Food : 13% markup
 * Electronics : 2% markup
 * Everything else : no markup
 
Example 1:
  Input $1,299.99, 3 people, food
  Oupput $1,591.58
  

