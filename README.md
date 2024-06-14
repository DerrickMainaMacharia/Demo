from docx import Document

# Create a new Document
doc = Document()

# Title
doc.add_heading('Budget for Dignity for All: Pad Drive 2024', level=1)

# Revenue Section
doc.add_heading('Revenue', level=2)

# Sponsorships
doc.add_heading('Sponsorships:', level=3)
doc.add_paragraph('Local Businesses and Corporate Sponsorships: KES 200,000')
doc.add_paragraph('Expected to be collected from various local businesses and corporate sponsors who will be acknowledged during the event and through promotional materials.')

# Donations
doc.add_heading('Donations:', level=3)
doc.add_paragraph('Individual Donations: KES 100,000')
doc.add_paragraph('Collected from community members and attendees who wish to support the cause either online or at the event.')

# Total Revenue
doc.add_paragraph('Total Revenue: KES 300,000', style='Intense Quote')

# Expenses Section
doc.add_heading('Expenses', level=2)

# Venue Rental
doc.add_heading('Venue Rental:', level=3)
doc.add_paragraph('Community Hall Rental: KES 50,000')
doc.add_paragraph('Cost of renting the community hall for the entire duration of the event, including setup and cleanup time.')

# Marketing and Promotion
doc.add_heading('Marketing and Promotion:', level=3)
doc.add_paragraph('Social Media Campaign: KES 10,000')
doc.add_paragraph('Budget allocated for promoting the event on social media platforms.')
doc.add_paragraph('Flyers and Posters: KES 10,000')
doc.add_paragraph('Printing and distribution of promotional materials.')
doc.add_paragraph('Local Media Advertisements: KES 10,000')
doc.add_paragraph('Advertisements in local newspapers, radio stations, and TV channels to raise awareness about the event.')

# Refreshments
doc.add_heading('Refreshments:', level=3)
doc.add_paragraph('Snacks and Drinks: KES 20,000')
doc.add_paragraph('Providing light snacks and beverages for all participants and volunteers during the event.')

# Educational Materials
doc.add_heading('Educational Materials:', level=3)
doc.add_paragraph('Workshop Materials: KES 15,000')
doc.add_paragraph('Pamphlets, brochures, and other materials needed for the educational sessions on menstrual hygiene management.')

# Entertainment
doc.add_heading('Entertainment:', level=3)
doc.add_paragraph('Performances and Speakers: KES 10,000')
doc.add_paragraph('Fees for local bands, dance performers, and motivational speakers who will engage the audience.')

# Miscellaneous
doc.add_heading('Miscellaneous:', level=3)
doc.add_paragraph('Miscellaneous Supplies: KES 5,000')
doc.add_paragraph('Any unforeseen expenses such as additional supplies or last-minute purchases needed for the event.')

# Total Expenses
doc.add_paragraph('Total Expenses: KES 130,000', style='Intense Quote')

# Net Revenue
doc.add_heading('Net Revenue', level=2)
doc.add_paragraph('Total Revenue: KES 300,000')
doc.add_paragraph('Total Expenses: KES 130,000')
doc.add_paragraph('Net Revenue: KES 170,000', style='Intense Quote')

# Save the document
file_path_doc = "/mnt/data/Pad_Drive_Budget_Proposal.docx"
doc.save(file_path_doc)

file_path_doc
