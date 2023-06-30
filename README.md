class Attributes(Tekky):
	@staticmethod
	def contact() -> tuple:
	    discord  = "tekky#1810"
	    telegram = "t.me/xtekky"
	    proton   = "github@g4f.ai"
	    
	    return discord, telegram, proton
	
	@staticmethod
	def life() -> tuple:
		langs         = ['French', 'German', 'Spanish', 'English']
		age           = 17
		
		return langs, age
	
	@staticmethod
	def coding() -> tuple:
		langs = {
			'expert':   ['python'],
			'intermediate': ['go', 'js'],
			'learning': ['c', 'c++', 'c#', 'asm', 'java']
		}
		specialities  = ['web/app reverse engineering', 'fullstack']
		environnement = ['vscode']
		
		return langs, specialities, environnement
