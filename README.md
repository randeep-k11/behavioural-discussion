# behavioural-discussion
1. **Tell me about a situation where you had a conflict with a teammate **
   * Scenario
     * Imagine you're working on a software development team building a high-scalability social media platform (like your Facebook clone). You're responsible for designing the database 
       schema, while another teammate is in charge of the backend API. Your teammate insists on using a NoSQL database because they believe it will be easier to scale, but you've done 
       extensive research and strongly believe that PostgreSQL, with proper indexing and partitioning, will be more efficient for relational data like friend connections and comments.
    * Conflict:  Your teammate refuses to consider PostgreSQL and insists that NoSQL is the only way forward. This creates tension as both of you feel strongly about your approach. 
      Discussions become unproductive, and deadlines start slipping.
    * Resolution: 
        * Gather Data: You decide to benchmark both approaches using a sample dataset and load tests.
        * Facilitate Discussion: Instead of arguing, you propose a meeting where you present objective findings.
        * Compromise: After seeing the results, you both agree on a hybrid approach—using PostgreSQL for structured relational data and NoSQL for less structured data like activity 
         logs.
        * Align with Goals: You both refocus on the project’s scalability needs and work together to optimize the final architecture.
    * Lesson Learned: Conflict resolution is not about proving who’s right but finding the best solution for the team and project. By staying professional, gathering data, and 
      fostering open discussions, you can turn conflicts into productive collaborations.
