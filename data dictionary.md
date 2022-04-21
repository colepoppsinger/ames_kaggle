{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "dd0f9baf-ed96-41b0-ad31-148bca2ea312",
   "metadata": {},
   "outputs": [],
   "source": [
    "### Data Dictionary\n",
    "\n",
    "This data dictionary provides a quick overview of features/variables/columns, alongside data types and descriptions. \n",
    "\n",
    "|Feature|Type|Source|Description|\n",
    "|---|---|---|---|\n",
    "|**overall_qual**|*int*|train.csv|Rates the overall material and finish of the house|\n",
    "|**gr_liv_area**|*int*|train.csv|Above grade (ground) living area square feet| \n",
    "|**year_remod/add**|*int*|train.csv|Remodel date (same as construction date if no remodeling or additions)| \n",
    "|**total_bsmt_sf**|*float*|train.csv|Total square feet of basement area| \n",
    "|**exter_qual_num**|*int*|train.csv|Evaluates the quality of the material on the exterior, converted to a numeric range| \n",
    "|**kitchen_qual_num**|*int*|train.csv|Kitchen quality, converted to a numeric range|\n",
    "|**bsmt_qual_num**|*float*|train.csv|Evaluates the height of the basement, converted to a numeric range|\n",
    "|**garage_area**|*float*|train.csv|Size of garage in square feet|\n",
    "|**garage_cars**|*float*|train.csv|Size of garage in car capacity|\n",
    "|**total_bsmt_sf**|*float*|train.csv|Total square feet of basement area|\n",
    "|**garage_finish**|*int*|train.csv|Interior finish of the garage, converted to a numeric range|\n",
    "|**overall_qual_liv_area**|*float*|train.csv|Interaction column, using **overall_qual * gr_liv_area** columns|\n",
    "|**overall_qual_squared**|*int*|train.csv|Engineered column, using the **square of the overall_qual** column|\n",
    "|**quality_and_age**|*int*|train.csv|Interaction column, using **overall_qual * year_remod/add** columns|\n",
    "|**house_total_sq**|*float*|train.csv|Engineered column, using **total_bsmt_sf + gr_liv_area/add** columns |\n",
    "|**year_remod_or_built**|*int*|train.csv|Interaction column, using **year_remod/add * year_built** columns|\n",
    "|**year_remod_or_built_sq**|*int*|train.csv|Engineered column, using the **square of the year_remod_or_built** column|"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
