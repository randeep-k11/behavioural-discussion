# behavioural-discussion
1. **Tell me about a situation where you had a conflict with a teammate**
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

   * **Scenario: Code Quality vs. Deadline Pressure**
     * You're working with a teammate on the backend API, and they frequently commit code that works but lacks proper documentation, has inefficient queries, or contains unoptimized 
       logic. You suggest improving the code quality, but they argue that meeting the deadline is more important.
     * Conflict: Your teammate sees your insistence on clean code as a delay, while you see their rushed approach as technical debt that will cause problems later.
     * Resolution: 
         * You suggest a middle ground: merging the working code now but scheduling a refactor sprint after the feature launch.
         * You propose implementing code reviews to balance speed and quality.
         * You demonstrate how small optimizations improve performance and reduce future debugging time.
     * Lesson Learned: Balancing speed and quality is key in software development. Finding a compromise ensures deadlines are met without sacrificing long-term maintainability.
   * **Scenario: Feature Prioritization Dispute**
     * Situation: You're in a sprint planning meeting, and you believe optimizing the database indexing should be a priority, but another teammate argues that developing a new chat 
       feature is more urgent.
     * Conflict: You believe scalability concerns should be addressed early, while your teammate insists on delivering user-facing features first.
     * Resolution:
        * You bring in data, showing that slow queries are already affecting some users.
        * You suggest a compromise: dedicating part of the sprint to indexing while also making progress on the chat feature.
        * The team collectively decides based on impact vs. urgency.
     * Lesson Learned: Prioritization should be driven by data, not just opinions. Finding a balance between backend optimizations and user-facing features ensures long-term success.
2. **In your professional experience have you worked on something without getting approval from your manager?**
   * **Scenario: Refactoring Code Without Prior Approval**
     * Situation: While working on a new feature, you notice that an existing database query is inefficient, causing slow performance. The query isn't directly related to your task, 
       but fixing it would improve overall system speed.
     * Action Without Approval:
         * You refactor the query to be more efficient and optimize indexes without officially adding it to the sprint.
         * You push the update along with your assigned task.
     * Outcome:
         * The system’s response time improves, and your teammates appreciate the proactive fix.
         * Your manager later acknowledges the improvement but asks for such changes to be documented in future sprints.
     * Lesson Learned: Small improvements can make a big difference, but tracking changes ensures visibility and avoids unintended side effects.
  * **Scenario : Fixing a Critical Bug in Production Without Waiting for Approval**
    * Situation: You're monitoring your Facebook clone’s production logs and notice a major issue: user profile pictures are not loading due to a misconfigured database query. Users 
      are complaining, and engagement is dropping.
    * Action Without Approval:
        * Instead of waiting for a formal approval process, you immediately roll out a quick fix and deploy it.
        * You document the issue and notify the team after the fix is live.
    * Outcome:
        * The issue is resolved quickly, minimizing user impact.
        * Your manager later appreciates the initiative but reminds the team to follow escalation procedures in the future.
    * Lesson Learned: Sometimes, taking initiative is necessary, but it's important to communicate changes and improve processes to avoid similar emergencies.



    
 
      
  


