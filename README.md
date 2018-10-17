# some-instructrion-about-plotting-panda-new
- import pandas
- df = pandas.read_csv('data/gapminder_gdp_oceania.csv')
- oceania_plot = df['gdpPercap_1952'].plot()
- oceania_plot.figure.savefig('oceania.png')
