## Many-to-Many relationships in Spring Boot

This Baeldung reading offers some great insight into how to exercise a bit more control over your database schema while using Spring Data JPA. They manually create SQL tables using traditional SQL queries, and then wire their Spring Entities using various `javax.persistence` annotations. I like this approach a great deal more as I prefer to write SQL queries myself wherever possible. I think that SQL is designed almost in particular to not be complex (unless it has to be), and the layers which Spring hides it behind in the case of even simple relationships between data is often totally confounding.

## Security paper

I think this humorous paper effectively highlights the huge divide between pragmatism and rigor in the computer science world. Each camp will always have its fervent advocates. I am interested in the arguments of both, but question whether either party can have its way at scale, which is really the essential point. Probably we need to reconsider the scope of our systems and their ultimate aims if we are going to have security up to a truly acceptable standard. On the other hand, I am somewhat skeptical of the idea that there are malicious actors in the amount that many people suppose; I think Hanlon's razor is in effect here: never attribute to malice what you can attribute to stupidity.