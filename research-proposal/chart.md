# Plotting with weeks on the x-axis and tasks on the y-axis
fig, ax = plt.subplots(figsize=(14, 8))
ax.barh(df['Works'], (df['End Date'] - df['Start Date']).dt.days, left=df['Start Date'].map(mdates.date2num), color='lightgreen')
ax.xaxis_date()
ax.xaxis.set_major_locator(mdates.WeekdayLocator(interval=1))
ax.xaxis.set_major_formatter(mdates.DateFormatter("%b %d, %Y"))
plt.xticks(rotation=45)
ax.set_xlabel('Week')
ax.set_ylabel('Tasks')
ax.set_title('Project Timeline: Tasks by Week')

plt.tight_layout()
plt.show()
