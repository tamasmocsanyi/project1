# new
projects
'type_count=books['bet_type'].value_counts().reset_index().head(15)

plt.figure(figsize=(8, 8))
ax=sns.barplot(x='count', y='bet_type',data=type_count,palette='cividis',hue='bet_type')
for p in ax.patches:
    ax.annotate(f'{p.get_width():.0f}', (p.get_width(),p.get_y() + p.get_height()/2),
                va='center')
plt.title('Top 15 Bet Types',fontdict={'fontsize':16,'fontweight':'bold','fontfamily':'Verdana'})
plt.ylabel(None)
plt.xlabel(None)
plt.show()e'
