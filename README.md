# Can Sentiment Analysis Reveal Structure in a "Plotless" Novel?

## About This Research

**Author**: Katherine L. Elkins, Ph.D.  
**Co-Author**: Jon Chun

This repository contains materials related to the early research paper "Can Sentiment Analysis Reveal Structure in a 'Plotless' Novel?" examining Virginia Woolf's *To the Lighthouse* through computational sentiment analysis.

## Research Significance

This work represents pioneering research in computational narratology, published in 2019. It was among the **first studies** to apply sentiment analysis methodologies to modernist literature, demonstrating that seemingly "plotless" modernist novels contain distinct emotional arcs and underlying narrative structures.

### Key Contributions

**Methodological Innovation:**
- Developed comparative approach using multiple sentiment analysis models (VADER, Syuzhet.R)
- Introduced "middle reading" methodology combining computational analysis with close literary reading
- Validated simple lexical approaches against more sophisticated sentiment detection methods

**Literary Discovery:**
- Introduced the concept of the **"distributed heroine model"** - showing how emotional arcs in modernist fiction distribute across multiple characters rather than following a single protagonist
- Demonstrated that Woolf's *To the Lighthouse*, while lacking traditional plot structure, exhibits strong underlying emotional architecture
- Revealed thematic patterns of connection/separation, coherence/dissolution across the novel

**Theoretical Framework:**
- Established methods for analyzing "relative" vs "absolute" emotional valence in narrative
- Developed approaches for handling emotionally ambivalent or contradictory moments in modernist texts
- Created framework for selecting appropriate smoothing techniques (DCT, LOESS, Rolling Mean) for different analytical purposes

## Foundational Work

This research laid the groundwork for:
- The SentimentArcs methodology published in *The Shapes of Stories* (Cambridge University Press, 2022)
- Broader applications of computational sentiment analysis across literary texts, medical narratives, social media discourse, and policy documents
- Integration of humanistic close reading with computational distant reading approaches

## Publication

Elkins, K. & Chun, J. (2019). "Can Sentiment Analysis Reveal Structure in a 'Plotless' Novel?" arXiv:1910.01441v1.

**Read the paper**: [arXiv:1910.01441](https://arxiv.org/abs/1910.01441)

## Methodology Overview

### Sentiment Analysis Techniques

The study employed multiple approaches:
- **Lexical sentiment analysis** using Syuzhet.R
- **VADER** (Valence Aware Dictionary and sEntiment Reasoner) for validation
- Multiple smoothing methods: DCT (Discrete Cosine Transform), LOESS, Rolling Mean

### Novel Analysis

Analyzed Virginia Woolf's *To the Lighthouse* to:
- Test whether modernist fiction exhibits traditional narrative arcs
- Examine how emotional valence patterns reveal underlying structure
- Compare computational findings with traditional literary criticism

### Validation

- Compared simple vs. sophisticated sentiment detection approaches
- Validated computational results against human expert interpretation
- Tested against randomized "word salad" versions to verify intentional structure

## Key Findings

1. **Modernist novels contain strong emotional arcs**: Despite lacking traditional plot structure, *To the Lighthouse* exhibits distinct patterns of emotional valence

2. **Distributed narrative structure**: Emotional highs and lows distribute across multiple characters, creating a "distributed heroine" rather than following a single protagonist

3. **Thematic patterns correlate with emotional arcs**: 
   - Moments of connection and coherence = emotional highs
   - Moments of separation and dissolution = emotional lows
   - Ambivalent emotions register as "neutral" valence

4. **Simple lexical approaches work surprisingly well**: Comparison with VADER showed that basic sentiment analysis performs remarkably well on literary texts

## Implications for Digital Humanities

This work demonstrates:
- **Computational methods can reveal hidden structures** in texts thought to break with narrative convention
- **Middle reading** (between close and distant reading) offers unique insights
- **Humanistic expertise + computational tools** produce richer analysis than either alone
- **Literary language**, despite its complexity, is amenable to computational analysis when methods are carefully validated

## Related Work

This research contributed to:
- **The Shapes of Stories** (Cambridge UP, 2022) - comprehensive methodology for sentiment analysis of narrative
- Comparative studies of narrative emotional structure across cultures and media
- Development of human-centered AI approaches to text analysis

## Repository Contents

- `paper/` - Full research paper (arXiv version)
- `docs/` - Additional documentation on methodology
- `examples/` - Sample analyses and visualizations

## Citation

If you use this work in your research, please cite:

```
Elkins, K., & Chun, J. (2019). Can Sentiment Analysis Reveal Structure in a 
"Plotless" Novel? arXiv preprint arXiv:1910.01441.
```

## Related Research

**By Katherine Elkins:**
- *The Shapes of Stories: Sentiment Analysis for Narrative* (Cambridge University Press, 2022)
- "Beyond Plot" *Journal of Cultural Analytics* (2025)
- "The Shapes of Cinderella: Emotional Architecture and the Language of Moral Difference" *Humanities* (2025)

## Contact

**Katherine L. Elkins, Ph.D.**  
Professor of Humanities and Comparative Literature  
Kenyon College  
Email: elkinsk@kenyon.edu

## Acknowledgments

This research was conducted at the KDH AI Collaboratory, Kenyon College. Special thanks to the digital humanities community for feedback on early versions of this work.

## License

This repository is licensed under the MIT License. See LICENSE file for details.

---

*This work represents early computational humanities research (2019) that helped establish sentiment analysis as a valuable tool for analyzing narrative structure in literary texts.*
