# Cybersecurity Analysis using Cosine Similarity
*What is Cosine similarity:* <br>
Cosine similarity is a metric used to measure the similarity in direction between two vectors, ignoring their size (or magnitude).<br>
Consider two arrows (vectors) starting from the same point, then;<br>
-	If the arrows point in the exact same direction, their cosine similarity is 1.
-	If the arrows are perpendicular (forming a 90-degree angle), their cosine similarity is 0. This means they are "unrelated" in direction.
-	If the arrows point in opposite directions, their cosine similarity is -1.
## Mathematics of Cosine Similarity
It is calculated by finding the cosine of the angle $\theta$  between the two vectors $A$ and $B$:<br>
$$\cos(\theta)=\frac{A\cdot B}{|A||B|}$$
\\Where;
- ${A\cdot B}$ A.B is the dot product of the vectors (a measure of how much one vector "goes along" with the other).
- $|A|$ and $|B|$  ‖A‖  and ‖B‖ are the magnitudes (or lengths) of the vectors.

