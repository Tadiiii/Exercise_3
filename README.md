# Exercise_3

1) First steps on GitHub

GitHub: https://github.com/Tadiiii/Exercise_3
GIT-TOKEN: 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

git commit -m “[descriptive message]” = commit your staged content as a new commit snapshot
git push [alias] [branch]= Transmit local branch commits to the remote repository branch
git pull = fetch and merge any commits from the tracking remote branch

2) Map plots

The function plots the dataframe on a world card. Therefore you have to give him the variable of your data. That the function can work with the dataset it must be 2D and in the form (time, lat, lon) so you also have to transform the data before if necessary.
For example: 
era = xr.open_dataset('/users/students/a11720615/Exercise1/era5_2m_temperature_1950-2021_monthly.nc')['t2m']
