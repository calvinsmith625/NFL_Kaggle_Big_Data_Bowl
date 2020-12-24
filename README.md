# Tracking Data Project - Determine which defensive backs are most effective in different roles from tracking data captured at 10 frames per second.

calvin-smith-data-clean: Initial data acquisition and cleaning notebook. This notebook cleans over 15 million rows in order for it be exported in a format that is simpler to engineer features from.

coverage-id: Develop model to determine man or zone coverage from data engineered in merge-data-clean and calvin-smith-data-clean notebooks. This notebook derives additional features to provide more context to each play to evaluate defensive back movements.

bdb-randomforest: Utilizes object oriented programming to train a Random Forest Classifier to predict pass completion probability.
