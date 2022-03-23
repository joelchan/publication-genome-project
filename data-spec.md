a good dataset could have evidence data of the following form:
- paper identifier (doi > semantic scholar id > url)
- evidence statement as a single sentence that can be interpreted in a standalone way
- optionally, evidence description (free-form paragraph, against should be interpretable on its own)
- snippets from the paper that jointly can be summarized into the evidence statement, each with page it’s from
- optionally, snippets from the paper that can be summarized into the evidence description, each with page it’s from
- centrality: how central is this evidence to the paper’s results, 1-10?

given an evidence set like this, it would also be nice to know for each mentioned paper how complete the set is - what fraction of the evidence mentioned in the paper is covered? this would help us judge recall of automated extraction methods (whereas if we only have the evidence data itself, we can only judge precision)
